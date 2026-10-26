# Rinston

AI phone front desk: US numbers so agents can call and text via MCP.

## MCP server (live)
`https://rinston.com/api/agent/mcp` (Streamable HTTP)

## Auth: current status
- **OAuth 2.1 + PKCE:** only for pre-registered clients. Dynamic Client Registration (DCR) is **not** supported yet.
- **Agent bearer key:** works today. Mint one in your rinston.com account and send it as `Authorization: Bearer <key>`.

## Install
Use the Grok Bot / Cursor plugin package in this repo, or point any MCP client at the URL above with a bearer key.

## Known gaps
- The privacy and terms pages on rinston.com still return 404.
- Not listed in the marketplace yet.

MIT licensed.
