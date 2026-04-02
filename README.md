## Hi, I'm @lucid-jin 👋

I'm interested in React, TypeScript, and building developer tools.

### 🔧 Projects

#### [mcpick](https://github.com/lucid-jin/mcpick) — Pick and sync MCP server configs across AI tools

> Sync MCP configurations between Claude Code, Claude Desktop, Cursor, Codex, Gemini CLI, and Copilot CLI with a single command or web dashboard.

- **CLI**: `mcpicker list` / `mcpicker sync` / `mcpicker doctor`
- **Dashboard**: `mcpicker dashboard` — drag-and-drop MCP sync at localhost:4747
- **Auto-conversion**: HTTP ↔ mcp-remote, path resolution
- **Stack**: Bun / TypeScript / Node.js compatible

```bash
# See all your MCP servers across every AI tool
node dist/index.js list

# Sync with auto HTTP conversion
node dist/index.js sync claude-code claude-desktop

# Web dashboard
node dist/index.js dashboard
```

