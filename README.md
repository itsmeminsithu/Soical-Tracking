# Soical-Tracking

Note: this repository is a skeleton, not a runnable app. The name is spelled
Soical-Tracking in this repository.

## What is actually here

- `index.tsx` — React entry point that renders `App` from `./App`. `App`
  is not in the repository, so this file cannot run as-is.
- `.github/workflows/webpack.yml` — CI workflow that runs `npm install`
  and `npx webpack`. There is no `package.json`, so this workflow cannot
  succeed until a real project is restored.
- `LICENSE` — GNU Lesser General Public License v2.1 (full text).
- `.gitignore` — Node / Vite ignores.

## What is missing

No `package.json`, no `index.html`, no `App` component, no Vite or
Webpack config, and no backend code. The previous README described a
Node.js + Express backend, Instagram Graph API, and React + Vite
frontend, but none of that code is in the repository.

## Status: decision needed

Do not treat this as a working Instagram Story Viewer. The owner needs
to decide: restore the full project from an outside copy, or archive
the repository. This change only fixes the README and `.gitignore`; it
does not invent the missing app, and there is no live preview for a
skeleton — a Pages preview is only honest once a real app is restored.

## License

LGPL-2.1 — see `LICENSE`.
