## Agent repository structure

This repository organizes agent guidance and standards into a few canonical locations:

- `AGENTS.md`: primary project playbook with repository-wide conventions.
- `.agents/agents/`: agent profile definitions (for example, role-specific behavior and scope).
- `.agents/skills/`: reusable task playbooks/skills that agents can apply across tasks.
- `docs/`: documentation and engineering standards (architecture, quality, security, testing, and time conventions).

### Related entry files

- `CODEX.md`, `CLAUDE.md`, `GEMINI.md`, `.junie/guidelines.md` point to or align with the shared `AGENTS.md` policy so different agent entrypoints stay consistent.