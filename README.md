# mcp-installer - A MCP Server to install MCP Servers

This server is a server that installs other MCP servers for you. Install it, and you can ask Claude to install MCP servers hosted in npm or PyPi for you. Requires `npx` and `uv` to be installed for[...]

![image](https://github.com/user-attachments/assets/d082e614-b4bc-485c-a7c5-f80680348793)

### How to install:

Put this into your `claude_desktop_config.json` (either at `~/Library/Application Support/Claude` on macOS or `C:\Users\NAME\AppData\Roaming\Claude` on Windows):

```json
  "mcpServers": {
    "mcp-installer": {
      "command": "npx",
      "args": [
        "@ndryer/mcp-installer"
      ]
    }
  }
