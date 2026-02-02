# MCP Servers Configuration

This workspace is configured to use Model Context Protocol (MCP) servers for enhanced workflow. MCP servers are available through:

## Setup

1. **GitHub Token** - Set `GITHUB_TOKEN` environment variable for GitHub MCP server:
   ```bash
   export GITHUB_TOKEN=ghp_your_token_here
   ```

2. **Install MCP Servers** (optional manual install):
   ```bash
   npm install --save-dev @modelcontextprotocol/server-github
   npm install --save-dev @modelcontextprotocol/server-filesystem
   npm install --save-dev @modelcontextprotocol/server-web
   ```

## Available MCP Servers

- **GitHub**: PR/issue management, repo operations, branch handling
- **Filesystem**: File operations with proper sandboxing
- **Web**: Web search and content fetching capabilities

These are automatically configured in `.mcpservers.json` and can be used via the MCP protocol.
