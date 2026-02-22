# skills

> A collection of [skills.sh](https://skills.sh) skills for React development — install them into any AI coding agent to get consistent, expert-level output.

## Install a Skill

```bash
npx skills add rutpshah/skills@<react-testing-best-practices>
```

Works with Claude Code, Cursor, GitHub Copilot, Aider, and more.

---

## Available Skills

| Skill                                                             | Description                                                                | Installs                                                                                                                                                                                                                           |
| ----------------------------------------------------------------- | -------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [`react-testing-best-practices`](./react-testing-best-practices/) | RTL, Vitest, Jest, MSW — test React components, hooks, forms & async flows | [![installs](https://img.shields.io/badge/dynamic/json?url=https://skills.sh/api/installs/rutpshah/skills@react-testing-best-practices&label=installs&color=blue)](https://skills.sh/rutpshah/skills/react-testing-best-practices) |

### Coming Soon

| Skill                    | Description                                                                  |
| ------------------------ | ---------------------------------------------------------------------------- |
| `react-state-management` | Zustand, TanStack Query, Jotai — patterns for managing client & server state |
| `react-forms`            | React Hook Form + Zod — validation, submission, error handling               |
| `react-typescript`       | Generic components, typed hooks, `forwardRef`, discriminated unions          |
| `react-accessibility`    | ARIA patterns, keyboard navigation, focus management                         |

---

## Why a Single Repo?

Following the convention of [`vercel-labs/agent-skills`](https://github.com/vercel-labs/agent-skills), grouping related skills in one repo makes them easier to discover, maintain, and version together.

---

## Contributing

Have a React pattern that AI agents consistently get wrong? Contribute a skill or improve an existing one.

1. Fork this repo
2. Create a new folder: `skills/your-skill-name/`
3. Add a `SKILL.md` (required) and optionally a `references/` folder for detailed examples
4. Open a PR — describe what agent behavior it fixes or improves

### Skill structure

```
your-skill-name/
├── SKILL.md              # Required — core instructions for the agent (keep under 500 lines)
├── README.md             # Required — installation & usage docs
└── references/           # Optional — verbose patterns loaded on demand
    └── *.md
```

### What makes a good skill?

- Fixes a **recurring mistake** AI agents make in React codebases
- Is **tool-specific** (e.g. "use MSW, not vi.mock for API calls")
- Has **concrete code examples**, not just principles
- Is **opinionated** — agents need clear guidance, not "it depends"

---

## License

MIT
