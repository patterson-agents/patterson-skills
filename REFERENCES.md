# References

## Deprecation

This marketplace is **deprecated** (2026-08-12). See the `[!CAUTION]` banner at the top of
[README.md](README.md) for the current state. Canonical pointers:

- **`patterson-marketplace`** (marketplace name `patterson`) is the canonical plugin catalog —
  [`patterson-agents/patterson-marketplace`](https://github.com/patterson-agents/patterson-marketplace).
- **`patterson-corp`** hosts governed org-wide plugins —
  [`patterson-agents/patterson-corp`](https://github.com/patterson-agents/patterson-corp).
- The `agentic-workflow-designer` skill formerly in this repo now lives in `patterson-labs`'s
  `patterson-workflows` plugin.
- Existing installs of `patterson-design@patterson-skills` keep working; no new content will
  land here.

## History and governance

The `patterson-design` plugin-name collision between this repo and `patterson-marketplace` was
resolved by retiring this repo's copy — see
[`patterson-corp` ADR 0003 — Plugin name reconciliation](https://github.com/patterson-agents/patterson-corp/blob/main/docs/decisions/0003-plugin-name-reconciliation.md),
Collision A. That record also notes that the `deprecated: true` machine-readable flag has not
yet been added to `.claude-plugin/marketplace.json` — only the description prefix and this
README banner mark deprecation.

`patterson-marketplace` was consolidated from the working marketplace this repo shipped first —
see `patterson-marketplace/.claude/plans/building-the-patterson-marketplace.md`.

## Brand assets

`docs/assets/patterson-logo-navy.svg`, `docs/assets/patterson-logo-white.svg`,
`docs/assets/patterson-logo-square-navy.svg`, and `docs/assets/banner.svg` are copied from
[`patterson-agents/patterson-corp`](https://github.com/patterson-agents/patterson-corp)'s
`docs/assets/`.
