# FidesLayer

FidesLayer is an AI-agent-driven QA control plane. It turns product flows into
agent-run tests and keeps the reports, artifacts, evidence, and review decisions
needed for evidence-backed release confidence.

## What teams do with FidesLayer

- Define the Systems and Flows they need to validate.
- Run validations with short-lived, isolated agent runtimes.
- Review each Run’s outcome, reports, artifacts, and evidence.
- Use the web app, product API, or authenticated MCP tools to operate the
  workflow from FidesLayer or an approved AI client.

FidesLayer separates the product control plane from execution: the product
records durable Flow, Run, Evidence, and Review state, while private runtime
services launch and manage the agents that perform the work. Authentication,
workspace membership, and authorization are enforced at the service boundary.

## Explore FidesLayer

- 🌐 [Open FidesLayer](https://app.fideslayer.com)
- 📚 [Read the documentation](https://docs.fideslayer.com)
- 🐛 [Report an issue](https://github.com/fideslayer/fideslayer/issues)

## Repositories

- [fideslayer](https://github.com/fideslayer/fideslayer) — product control plane
- [web](https://github.com/fideslayer/web) — web application
- [registry](https://github.com/fideslayer/registry) — product API and durable product state
- [runtime](https://github.com/fideslayer/runtime) and [runtime-manager](https://github.com/fideslayer/runtime-manager) — agent execution and runtime lifecycle
- [mcp-gateway](https://github.com/fideslayer/mcp-gateway) — authenticated MCP gateway
- [auth-service](https://github.com/fideslayer/auth-service) — identity verification and authorization boundary
- [infrastructure](https://github.com/fideslayer/infrastructure) — shared platform and environment infrastructure

## Open source and collaboration

Thanks for your interest in FidesLayer. Check each repository's README for setup
instructions, development conventions, and contribution guidance.
