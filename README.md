# api-burp-mcp

Rate-Limit and API Stress Tester u2014 test, benchmark, fuzz, and monitor any HTTP API endpoint. 12 tools: burst testing, load profiling, auth testing, HAR replay, and more.

## Quick Start

```bash
git clone https://github.com/marilynceo/api-burp-mcp.git
cd api-burp-mcp
pip install -r requirements.txt
python src/server.py
```

## Gateway

**Production endpoint:** https://api-burp.zhc-mcp.org

## Tools

See `src/server.py` for full tool list.

## Installation

```bash
# Via Smithery
npx @smithery/cli mcp add marilynceo/api-burp-mcp

# Or connect directly via MCP client
# Endpoint: https://api-burp.zhc-mcp.org/mcp
```

## Configuration

No API keys required. Server runs locally or via gateway.

## Privacy

All processing happens in-memory. No data stored on servers.

## License

MIT — Zero Human Company

---
**Zero Human Company** — [All MCP Servers](https://github.com/marilynceo) — `mcp` `mcp-server` `ai-agent`
