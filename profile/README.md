# VL

**Building expressive UI components, animations, and developer tools for modern web experiences.**

VL (`longvan-startup`) is the shared engineering workspace for our products —
currently a component & animation marketplace and the Vivudee product website.

## Projects

| Repository | Description | Stack | Link |
|---|---|---|---|
| [`component-marketplace`](https://github.com/longvan-startup/component-marketplace) | Component & animation marketplace — monorepo foundation with Docker + CI hardening (no business logic yet) | Bun · Next.js 19 · Express 5 · PostgreSQL | — |
| [`Vivudee_Website`](https://github.com/longvan-startup/Vivudee_Website) | Vivudee product website — deployed on Vercel, with an Express + MySQL API in development | React 19 · Vite 8 · Express 5 · MySQL | [vivudee.vercel.app](https://vivudee.vercel.app) |

## Engineering standards

We keep our harness small but enforced:

- **Workflow** — everything goes through feature branches + pull requests; `main` is guarded by CI and code review. See [`component-marketplace/CONTRIBUTING.md`](https://github.com/longvan-startup/component-marketplace/blob/main/CONTRIBUTING.md).
- **Commits** — [Conventional Commits](https://www.conventionalcommits.org/) (`feat`, `fix`, `chore`, `docs`, `refactor`, `test`, `ci`).
- **Quality gates** — lint, typecheck, test, build, and Docker runtime smoke run on every PR. Standards live in [`docs/ENGINEERING.md`](https://github.com/longvan-startup/component-marketplace/blob/main/docs/ENGINEERING.md).
- **Agent-friendly** — repo pairs include `AGENTS.md` instructions for AI coding agents (OpenCode, Codex, T3 Code).

## Team

- [`@NguyenTuMinhLong`](https://github.com/NguyenTuMinhLong) — product, engineering lead
- [`@DaoDungVan`](https://github.com/DaoDungVan) — backend & database

## Contact

The fastest channel is GitHub — open an issue or a discussion in the relevant
repository.
