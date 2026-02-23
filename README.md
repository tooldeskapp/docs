# ToolDesk Documentation

Documentation for ToolDesk, a macOS desktop application for building sandboxed web + Node.js applications with AI assistance.

## About ToolDesk

ToolDesk lets you build small applications combining a React frontend with a Node.js backend. Your code runs in a sandboxed environment, making it safe to experiment with AI-generated code.

## Documentation Structure

```
docs/
├── index.mdx                 # Overview
├── quickstart.mdx            # Getting started
├── installation.mdx          # Download and setup
├── concepts/                 # Core concepts
│   ├── workspace.mdx
│   ├── projects.mdx
│   └── sandbox.mdx
├── guides/                   # How-to guides
│   ├── creating-projects.mdx
│   ├── frontend-development.mdx
│   ├── backend-development.mdx
│   ├── calling-node-api.mdx
│   └── sandbox-permissions.mdx
├── api/                      # API reference
│   ├── node-api.mdx
│   └── shell-api.mdx
└── reference/
    └── project-structure.mdx
```

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview locally:

```bash
npm i -g mint
```

Run the development server:

```bash
mint dev
```

View at `http://localhost:3000`.

## Publishing

Install the Mintlify GitHub app from your [dashboard](https://dashboard.mintlify.com/settings/organization/github-app) to deploy automatically.

## Troubleshooting

- **Dev environment not running**: Run `mint update`
- **Page shows 404**: Ensure you're in the folder with `docs.json`
- **Check links**: Run `mint broken-links`
