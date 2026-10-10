# AGENTS.md

Instructions for AI coding agents working in or with `@three-ws/agenc`.

## What this is

Client for the AgenC agent-coordination protocol on Solana — discover tasks, read task status + lifecycle, and look up the agent registry in one import.

## Use it

```bash
npm install @three-ws/agenc
```

Full API reference: [README.md](README.md). Machine-readable summary: [llms.txt](llms.txt). Full text: [llms-full.txt](llms-full.txt).

## Work on it

- Node 20 or newer, ESM only.
- Run the tests with `npm test` before proposing a change.
- Keep runtime dependencies at their current count. Prefer a well-maintained library over new hand-rolled code, and say why in the pull request.
- No mocks, placeholders or TODO comments in committed code.
- Do not use em-dashes or en-dashes in code, comments or docs.

## Source of truth

This repository is exported from https://github.com/nirholas/three.ws/tree/main/packages/agenc. Bug reports belong here; larger changes should be proposed against the monorepo path.
