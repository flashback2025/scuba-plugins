# Scuba plugin

Connect your assistant to your saved context in [Scuba](https://scuba.app). Search and read Captures and Collections, save notes and links, and organize useful findings.

## Packages

- Root: portable Agent Plugin with Claude-compatible metadata.
- `openai/`: OpenAI package.
- `cursor/`: Cursor package.
- `claude/`: Claude package.
- `registry/server.json`: remote MCP server metadata.

The plugin connects to the hosted Scuba service at `https://api.scuba.app/mcp/`. An existing Scuba account is required. Sign in to your account when prompted by your client.

## Try it

- “Find the Capture about our onboarding decisions.”
- “Read my Product Research Collection and summarize the sources.”
- “Save this summary to Scuba as a text Capture.”

## Build packages

Run `python3 scripts/package.py --output /tmp/scuba-packages` to create platform ZIPs and checksums. This command only builds local archives.

The related [scuba-skills](https://github.com/flashback2025/scuba-skills) repository contains optional workflows for engineering memory and reviews.

## Privacy and terms

See [privacy](https://scuba.app/privacy) and [terms](https://scuba.app/terms).

## License

MIT. See [LICENSE](LICENSE).
