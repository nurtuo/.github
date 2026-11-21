# Nurtuo

**Open-source, AI-native integration platform.** Build, test, deploy and run integrations on a visual canvas or entirely through an AI agent (MCP), on a fast Go runtime that installs as a single binary next to your systems, with or without Docker.

- **Canvas + AI, one model.** The canvas and the AI agent edit the same compact JSON flow, validated by the same library.
- **Fast runtime.** One static Go binary, outbound-only hybrid agent, Windows service / systemd / launchd.
- **Deployable queues with push listeners.** Embedded NATS JetStream, no polling.
- **Everything free.** SSO/SAML, SCIM, RBAC, clusters and HA included. No paid edition.

> Status: early development. Nothing here is production-ready yet.

All code lives in the monorepo **[nurtuo/nurtuo](https://github.com/nurtuo/nurtuo)**. Start with its [README](https://github.com/nurtuo/nurtuo#readme), [architecture](https://github.com/nurtuo/nurtuo/blob/main/docs/ARCHITECTURE.md) and [contributing guide](https://github.com/nurtuo/nurtuo/blob/main/CONTRIBUTING.md).

Licensing: the server, runtime, control plane and UI are AGPLv3; SDKs, connectors, bridges, CLI and the flow schema are Apache-2.0.
