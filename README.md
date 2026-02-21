# oRPC Fullstack Agent Skill

An [Agent Skill](https://agentskills.io) for building fullstack typesafe APIs with [oRPC](https://orpc.unnoq.com) (v1.12+) and its ecosystem.

## What's Included

Comprehensive guidance covering the full oRPC stack:

- Contract-first development (define API shape, implement with type safety)
- Procedure definition, middleware, and routers
- Context flow and error handling (typed errors from contracts)
- Hono integration and server handler setup
- Client setup (fetch, WebSocket, batch, retry plugins)
- TanStack Query integration (queries, mutations, infinite queries, optimistic updates)
- Event iterators / SSE for real-time features
- File upload/download
- AI SDK integration

## Install

```bash
npx skills add stephen-golban/orpc-fullstack
```

## Structure

```
orpc-fullstack/
├── SKILL.md                    # Overview + quick reference (~250 lines)
└── references/
    └── REFERENCE.md            # Full detailed documentation with code examples
```

## License

MIT
