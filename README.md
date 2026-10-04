# scoop-bucket

[![Tests](https://github.com/marknefedov/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/marknefedov/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/marknefedov/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/marknefedov/scoop-bucket/actions/workflows/excavator.yml)

Personal bucket for [Scoop](https://scoop.sh), the Windows command-line installer.
Manifests are kept up to date automatically by the Excavator workflow, which runs every 4 hours.

## Install

```pwsh
scoop bucket add marknefedov https://github.com/marknefedov/scoop-bucket
scoop install marknefedov/agy-acp-server
```

## Manifests

| Manifest | Description |
| --- | --- |
| `agy-acp-server` | [Google Antigravity ACP server](https://github.com/agentclientprotocol/registry/tree/main/antigravity-acp) (`agy_acp_server.exe`). Version tracks the ACP registry. Sets `ANTIGRAVITY_HARNESS_PATH`. |
