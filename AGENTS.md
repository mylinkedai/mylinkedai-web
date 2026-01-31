# Repository Guidelines
- this a home page for LinkedAI company
- static web page, will be published to Github Pages
- LinkedAI app for receipt management, scan by AI
- share purchased item info with friend
- social app, chat and feeds
- create activity and invite friends
- generate text introduction and images

## Project Structure & Module Organization
This repository currently contains only this guide and no source tree. Create a clear top-level layout as the project grows (for example, `src/` for application code, `tests/` or `__tests__/` for tests, and `assets/` or `public/` for static files). If you introduce a framework, keep framework-specific directories in their conventional locations (e.g., `app/` for Next.js, `lib/` for shared utilities).

## Build, Test, and Development Commands
No build or test scripts are defined yet. When adding tooling, document the exact commands here and keep them in `package.json` or a Makefile. Example placeholders:
- `npm run dev`: start the local development server.
- `npm run build`: produce a production build.
- `npm test`: run the test suite.

## Coding Style & Naming Conventions
No language-specific style rules are established yet. When code is added, standardize on 2-space indentation for web code unless the framework dictates otherwise, and keep file and folder names consistent (e.g., `kebab-case` for files, `PascalCase` for components). Prefer explicit naming like `user-profile.tsx` over abbreviations. Add a formatter and linter (for example, Prettier and ESLint) and wire them to `npm run format` and `npm run lint`.

## Testing Guidelines
No testing framework is configured. Choose a framework that matches the stack (for example, Vitest/Jest for JS/TS, Playwright/Cypress for E2E). Place tests alongside modules or under a `tests/` root and name them `*.test.*` or `*.spec.*`. Document coverage expectations once a baseline exists.

## Commit & Pull Request Guidelines
There is no commit history to infer conventions. Use Conventional Commits (`feat:`, `fix:`, `chore:`) until a project-specific pattern is established. For pull requests, include a short summary, link related issues, and add screenshots or recordings for UI changes.

## Configuration & Secrets
Keep configuration in environment files (for example, `.env.local`) and do not commit secrets. Document required variables in a sample file such as `.env.example` when the project adds runtime configuration.
