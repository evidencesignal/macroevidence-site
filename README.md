# macroevidence-site

macroevidence.com — landing page and paid tier surface.

## Deploy

- **Root:** `index.html` (static). Netlify (or similar) connected to this repo deploys on push to `main`.
- **`/design.html`:** Redirects to `/` for old links.

## Data on the homepage (until automated)

After each pipeline output, update **hero numbers**, **regime tiles**, **Last Read / Next update** in `index.html`, then commit and push (or wire `fetch` to `latest.json` later).
