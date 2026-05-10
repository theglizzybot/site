# Site folder — Glizzy Bot

This repository contains a small static website for the Glizzy Bot project.
All homepage files are moved into the `site/` directory to keep the repository root tidy.

Contents
- `site/` — All public HTML pages, favicon and static assets for the homepage
  - `index.html` — Main landing page
  - `Glizzy-Bot-Landing.html` — Alternate landing page (kept for compatibility)
  - `documentation.html` — Documentation hub
  - `faq.html` — Frequently Asked Questions
  - `configuration.html` — Configuration guide
  - `api-reference.html` — API reference
  - `terms-of-service.html` — Terms of Service
  - `privacy-policy.html` — Privacy Policy

Serve locally

Use a simple static server (Node):

```bash
# from repository root
npx http-server site -p 8080
# or
python -m http.server 8080 --directory site
```

Notes
- I removed older duplicate website files from the repository root and `github/` copies to avoid confusion.
- Keep `favicon.jpg` in the repository root or move it into `site/` if you prefer. The pages reference `favicon.jpg` relative to the `site/` folder.

If you want, I can:
- move `favicon.jpg` into `site/` and update references;
- add a GitHub Pages workflow or `gh-pages` deployment config;
- commit and open a PR with these changes.
