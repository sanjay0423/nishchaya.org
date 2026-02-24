## Cursor Cloud specific instructions

This is a static "coming soon" landing page (single `index.html` + `CNAME` for GitHub Pages at `nishchaya.org`). There are **no build steps, no dependencies, and no package manager**.

### Running locally

Serve the site with any static HTTP server from the repo root:

```
python3 -m http.server 8080
```

Then open `http://localhost:8080` in a browser.

### Lint / Test / Build

- **Lint**: No linter is configured. You can optionally validate HTML with an external tool (e.g. `npx html-validate index.html`), but this is not part of the project.
- **Tests**: No automated tests exist.
- **Build**: No build step — the site is plain HTML/CSS served as-is.

### Notes

- Google Fonts are loaded from CDN; the page still renders with fallback fonts if offline.
- The `CNAME` file configures the GitHub Pages custom domain (`nishchaya.org`).
