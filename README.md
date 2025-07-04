# test-mcp

## Use Case of MCP Server

This project demonstrates the use of a Model Context Protocol (MCP) server. The MCP server acts as a bridge between your local environment and tools like GitHub Copilot, enabling advanced code completion, context-aware suggestions, and integration with external data sources or APIs.

### Key Features
- **Custom Context Providers:** Integrate your own data sources or APIs to enhance Copilot's suggestions.
- **Flexible Configuration:** Easily define new servers and inputs in the `.vscode/mcp.json` file.
- **Local or Remote Execution:** Run context providers locally or in containers for isolation and scalability.

## Integration with GitHub Copilot

By configuring the MCP server in your workspace, you can:
- Provide Copilot with additional context from your codebase, documentation, or external APIs.
- Customize how Copilot interprets and responds to your code and prompts.
- Use secure tokens and environment variables for authenticated integrations (e.g., with GitHub APIs).

### Example: GitHub Integration
The included configuration shows how to run a GitHub MCP server using Docker, passing a personal access token securely. This allows Copilot to:
- Fetch repository data
- Suggest code based on your GitHub projects
- Automate documentation and code review tasks

## Getting Started
1. Clone this repository and open it in VS Code.
2. Update `.vscode/mcp.json` and your workspace settings to define your MCP servers and required inputs.
3. Start the MCP server and use Copilot as usual—now with enhanced, context-aware suggestions!

## Documentation
- See the `.vscode/mcp.json` file for server configuration examples.
- Refer to the [GitHub Docs](https://github.com/github/docs) for more on Copilot and MCP integration.

---
