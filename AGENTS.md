# AGENTS.md

## Cursor Cloud specific instructions

This repository is a **GitHub profile README repo** (`wpjscc/wpjscc`). Its only content is
`README.md`, which GitHub renders on the user's profile page.

- There is **no application code, package manager, dependencies, services, build step, lint config, or test suite**. There is nothing to install, compile, serve, or test.
- The update script is intentionally a no-op; do not add dependency-install steps because there are no dependencies.
- The only "product" behavior is that `README.md` renders as Markdown. To preview it as GitHub would, render the Markdown to HTML (e.g. Python `markdown` or `pandoc`) and open it in a browser.
- The two badge images point to the external service `api.githubtrends.io`. They will show as broken images in an offline/egress-restricted environment; this is expected and not a repo problem.
