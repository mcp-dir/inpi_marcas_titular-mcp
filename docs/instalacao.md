# Instalação detalhada

INPI Marcas por CPF: CNPJ é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_inpi_marcas_titular`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_inpi_marcas_titular` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_inpi_marcas_titular` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_inpi_marcas_titular` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.inpi_marcas_titular` (ou `servers.inpi_marcas_titular` no VS Code) do config do cliente e reinicie.
