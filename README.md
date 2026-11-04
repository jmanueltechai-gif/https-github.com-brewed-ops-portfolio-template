# JM Manuel Portfolio

Personal portfolio project repository.

## Current status

This repository was empty when inspected on 4 November 2026. The live Vercel project, `portfolio-template`, currently deploys from `brewed-ops/portfolio-template` on the `main` branch. This repository is **not** the source currently connected to that Vercel project.

- Live site: https://portfolio-template-gilt-mu.vercel.app/
- App source has not been added here yet.
- Vercel settings and domains have not been changed.

## Recommended project layout

Keep application code and assets grouped by purpose:

```text
src/
  components/   Reusable interface pieces
  data/         Portfolio content and project details
  hooks/        Reusable React hooks
  lib/          Utilities and integrations
  styles/       Global styles and design tokens
public/
  images/       Public portfolio images
  icons/        Icons and logos
docs/
  screenshots/  Project screenshots and notes
scripts/        Small development utilities
```

Keep the root configuration files there too, such as `package.json`, `index.html`, `tsconfig.json`, and the Vite configuration. Generated output such as `dist/` and installed dependencies such as `node_modules/` should not be committed.

## When adding the portfolio source

1. Add the complete app source and its package lock file to this repository.
2. Run the documented checks from `package.json`, including the production build.
3. Review the resulting deployment before connecting this repository to the live Vercel project.

The current live project will continue deploying from its existing source until its Vercel Git connection is intentionally changed.
