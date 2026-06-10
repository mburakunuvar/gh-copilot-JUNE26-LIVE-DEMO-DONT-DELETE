# Demo Prompt Reference

This file captures the current, canonical issue/page model used by the demo workflows.

## Home Page Navigation Targets
1. GH Copilot in VS Code -> gh-copilot-vscode.html
2. GH Copilot in Web UI -> gh-copilot-web-ui.html
3. GH Copilot CLI -> gh-copilot-cli.html
4. GH Copilot SDK -> gh-copilot-sdk.html
5. GH Copilot App -> gh-copilot-app.html

## Active Issue Model (Setup Demo Issues)
1. Azure Container Apps Setup (`init-demo`)
2. Scaffold and Beautify the Home Page (`copilot-cli`)
3. GH Copilot in VS Code Page (`agent-mode`)
4. GH Copilot in Web UI Page (`coding-agent`)
5. GH Copilot CLI Page (`copilot-cli`)
6. GH Copilot SDK Page (`copilot-cli`)
7. GH Copilot App Page (`copilot-cli`)
8. Azure Deployment (`copilot-cli`)
9. Clean Up Azure Resources (`post-demo`)

## Source Links for Child Pages
- GH Copilot in VS Code: https://code.visualstudio.com/docs/agents/concepts/overview
- GH Copilot in Web UI:
  - https://docs.github.com/en/copilot/concepts/agents/cloud-agent/about-cloud-agent
  - https://docs.github.com/en/copilot/concepts/agents/code-review
- GH Copilot CLI: https://docs.github.com/en/copilot/how-tos/copilot-cli/use-copilot-cli/overview
- GH Copilot SDK: https://github.com/github/copilot-sdk?utm_source=blog-cli-sdk-repo-cta&utm_medium=blog&utm_campaign=cli-sdk-jan-2026
- GH Copilot App: https://github.com/github/app

## Notes
- Legacy pages are retired: custominstructions.html, skills.html, customagents.html, mcp.html, hooks.html.
- Keep `.github/workflows/setup-issues.yml`, `.github/workflows/auto-deploy.yml`, and `.github/ISSUE_TEMPLATE/*` aligned when changing issue titles.
