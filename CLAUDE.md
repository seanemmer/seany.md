# CLAUDE.md

## Mandatory Coding Practices

- **Type Driven Development** — Define types and interfaces first, then implement against them.
- **Test Driven Development** — Write failing tests before writing implementation code.
- **Intermediate Checking** — Run typechecks, tests, and Playwright MCP confirmation between implementation steps.

## Absolutely No Cheating

- No `@ts-ignore` or `@ts-expect-error`.
- No `eslint-disable` or `biome-ignore` comments.
- No type assertions (`as`, `!`) unless absolutely necessary.
- No skipping files or tests when running checks.

## Recommended Stack

### Underlying Technologies

- **Strict TypeScript** — All code uses TypeScript in strict mode with no `any` types.
- **Bun** — Package manager and test runner.
- **Biome** — Linter and formatter.

### Frontend

- **React** — UI component library.
- **Vite or Astro** — Use Vite for SPAs, Astro for static/content-driven sites.
- **Tailwind CSS** — Utility-first styling.
- **shadcn/ui** — Pre-built accessible component primitives.

### Backend

- **Bun** — Backend runtime.
- **GraphQL** — API query layer.
- **Drizzle** — Type-safe ORM.
- **Supabase** — Managed Postgres and auth.
