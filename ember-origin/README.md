# Ember & Origin — Specialty Coffee Storefront

A static, front-end-only e-commerce demo built with plain HTML, CSS, and JavaScript (no build tools, no dependencies).

## Features
- Product catalog with category filtering
- Cart drawer with quantity controls and live totals
- 3-step checkout flow (shipping → payment → review) with order confirmation
- Free-shipping threshold logic
- Fully client-side — state lives in memory and resets on page reload

## Run locally
Just open `index.html` in any browser, or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy
This is a static site — it can be hosted as-is on GitHub Pages, Netlify, Vercel, or any static host.

### GitHub Pages
1. Push this repo to GitHub.
2. Go to Settings → Pages → set source to the `main` branch, root folder.
3. Your site will be live at `https://<username>.github.io/<repo-name>/`.

## Note
This is a **front-end demo only** — no real payments are processed and no orders are persisted. Adding real transactions requires a backend (e.g. Node/Express) with a payment gateway (e.g. Stripe) and a database.

## License
MIT
