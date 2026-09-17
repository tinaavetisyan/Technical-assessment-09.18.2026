# Technical-assessment-09.18.2026

TailAdmin React dashboard (React 19, Vite 6, TypeScript, Tailwind CSS 4).

## Fixes

- **Home grid** — `gri` / `col-12` should be `grid` / `col-span-12`, dashboard layout was broken
- **Dropdown crash** — `&` used instead of `&&`, `contains` called on `null` when clicking outside
- **No Tailwind** — missing `postcss.config.js`, styles did not compile
- **Country map** — jVectorMap inits with width `0`, SVG transform becomes `Infinity`

## Run

```bash
npm install
npm run dev
```
