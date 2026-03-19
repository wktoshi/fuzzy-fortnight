# CLAUDE.md

This file provides guidance for AI assistants (Claude and others) working in this repository.

## Repository Overview

**Name:** fuzzy-fortnight
**Status:** Newly initialized — no source code exists yet.

This file will be updated as the codebase grows. Until then, it establishes baseline conventions for contributors and AI assistants.

---

## Repository Structure

```
fuzzy-fortnight/
└── CLAUDE.md          # This file
```

As the project evolves, the structure section should be updated to reflect actual directories and their purposes (e.g., `src/`, `tests/`, `docs/`, configuration files, etc.).

---

## Development Workflow

### Branch Conventions

- `main` — stable, production-ready code
- `claude/<description>-<id>` — AI-assisted feature/fix branches
- Feature branches should be short-lived and merged via pull request

### Commit Messages

Use the imperative mood and keep subject lines under 72 characters:

```
Add user authentication module
Fix off-by-one error in pagination logic
Refactor database connection pooling
```

### Pull Requests

- PRs should be focused on a single concern
- Include a summary of changes and a test plan in the PR description
- All CI checks must pass before merging

---

## Coding Conventions

Since no language or framework has been established yet, the following general guidelines apply:

- **Clarity over cleverness** — write code that is easy to read and understand
- **Minimal surface area** — only expose what is necessary; prefer small, focused functions/modules
- **No dead code** — remove unused code rather than commenting it out
- **Consistent naming** — follow the naming conventions of whichever language is adopted
- **No magic numbers** — use named constants for values that carry meaning

When a language/framework is chosen, update this section with language-specific style guides, linters, and formatter configurations.

---

## Testing

No test framework has been selected yet. When one is adopted:

- Document the test command here (e.g., `npm test`, `pytest`, `cargo test`)
- Describe where tests live relative to source files
- Note any required environment variables or fixtures

**Principle:** every non-trivial function should have at least one test. New features should include tests before merging.

---

## Environment Setup

No environment configuration exists yet. When the project is bootstrapped:

1. Document prerequisites (runtime version, package manager, etc.)
2. List setup steps (e.g., `npm install`, `pip install -r requirements.txt`)
3. Describe any required environment variables (use a `.env.example` file — never commit secrets)

---

## AI Assistant Guidelines

When working in this repository, AI assistants should:

1. **Read before editing** — always read the relevant files before making changes
2. **Make minimal changes** — only modify what is directly required by the task
3. **Follow existing style** — match the conventions already present in the codebase
4. **No unnecessary abstractions** — avoid creating helpers or utilities for one-off operations
5. **Avoid over-engineering** — keep solutions simple; do not add features beyond what is requested
6. **Do not commit secrets** — never commit API keys, passwords, or tokens
7. **Update this file** — when significant architectural decisions are made, update CLAUDE.md to reflect them
8. **Branch discipline** — develop on the designated feature branch; never push directly to `main`

---

## Key Files to Know

| File | Purpose |
|------|---------|
| `CLAUDE.md` | AI assistant guidance (this file) |

This table should be updated as important configuration files, entry points, and key modules are added to the project.

---

## Frequently Needed Commands

_To be filled in once the project is bootstrapped._

```bash
# Example placeholders — replace with real commands
# Install dependencies
# <package-manager> install

# Run tests
# <test-runner>

# Start development server
# <start-command>

# Lint / format
# <lint-command>
```
