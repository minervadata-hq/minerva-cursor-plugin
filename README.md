# Minerva for Cursor

A minimal Cursor plugin that connects to Minerva's hosted MCP service.

## Files

- `.cursor-plugin/plugin.json` — plugin name and metadata.
- `mcp.json` — the hosted endpoint: `https://api.minerva.io/mcp`.
- `assets/logo.png` — Minerva logo.
- `README.md` — this document.

The plugin contains no server implementation, customer data, credentials,
dependencies, executable scripts, skills, or hooks.

## Use

Load this directory using [Cursor's local plugin workflow](https://cursor.com/docs/plugins).
A Minerva account is required. Complete Minerva's OAuth sign-in in Cursor when
prompted. Existing account permissions and plan limits apply.

[Minerva MCP documentation](https://docs.minerva.io/minerva-data-mcp)

## Review status

Private draft for engineering and compliance review. Public release and an
open-source license have not been approved. This plugin is not listed in the
Cursor Marketplace.
