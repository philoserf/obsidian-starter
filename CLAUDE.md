# obsidian-starter

GitHub template repo for a minimal Obsidian vault. No build tools, tests, linting, or dependencies.

## Repository structure

```text
README.md          — project documentation (users remove after setup)
LICENSE            — MIT license
.obsidian/         — Obsidian app configuration (JSON files)
```

## Formatting

Markdown must pass prettier. Format with:

```bash
bunx prettier --write <file>
```

## Obsidian configuration

Five core plugins are enabled: file-explorer, switcher, backlink, command-palette, editor-status. All others are disabled. Files in `.obsidian/` are auto-managed by the Obsidian UI — edit them with care and preserve the existing minimalist set.

## Design philosophy

Minimalism is the core constraint. Changes must preserve it. Do not add plugins, themes, folder structures, sample notes, or templates. The vault is intentionally close to empty so users build their own system from scratch.
