# cuddly-rotary-phone

This repository is an early project scaffold. It currently contains repository documentation and GitHub automation for a future Node.js application, but no application source code has been added yet.

## Repository structure

```text
.
├── README.md
├── SECURITY.md
└── .github/
    ├── ISSUE_TEMPLATE/
    │   └── bug_report.md
    └── workflows/
        └── azure-webapps-node.yml
```

## What is included

- `README.md` — this overview of the current repository state.
- `SECURITY.md` — security reporting guidance for maintainers and contributors.
- `.github/ISSUE_TEMPLATE/bug_report.md` — a GitHub issue template for bug reports.
- `.github/workflows/azure-webapps-node.yml` — a GitHub Actions workflow scaffold for building and deploying a Node.js application to Azure Web App.

## Current status

There is not yet a runnable application in this repository. In particular, the repository does not currently include a `package.json`, source directory, test suite, or build configuration for an app.

The Azure workflow assumes a Node.js project will be added later. Before it can deploy successfully, update the workflow with a real Azure Web App name, configure the `AZURE_WEBAPP_PUBLISH_PROFILE` repository secret, and add the application files that `npm install`, `npm run build`, and `npm run test` should operate on.

## Suggested next steps

1. Define the purpose and scope of the application.
2. Add a Node.js project manifest such as `package.json`.
3. Add source code, tests, and any required build tooling.
4. Update the Azure Web App workflow configuration for the real deployment target.
5. Expand this README with local setup, development, testing, and deployment instructions.
