# CostEstimator — Static Link Hub

This repository contains a small static site (three files) that provides direct links to the following CostEstimator pages:

- https://costestimator.us/commercial-estimating/
- https://costestimator.us/preliminary-estimating/
- https://costestimator.us/lumber-takeoff/
- https://costestimator.us/framing-estimating/

## Files included

- `index.html` — landing page linking to each target URL, includes minimal SEO meta and JSON-LD.
- `style.css` — simple, modern CSS used by `index.html`.
- `README.md` — this file.

## How to use (quick)

1. Create a new GitHub repository (public or private).
2. Add `index.html` and `style.css` to the repo root.
3. Commit and push.
4. (Optional) Enable GitHub Pages:
   - Go to **Settings → Pages** (or **Settings → Pages** in new UI).
   - Select the branch (e.g. `main`) and `/ (root)` folder. Save.
   - GitHub Pages will publish your site at `https://<your-username>.github.io/<repo-name>/`.

## Notes & customization ideas

- Replace title, description and JSON-LD values with brand-specific copy if you own the target site.
- Add your own logo (replace the textual header) by adding an `img` element into `index.html` and adjusting CSS.
- If you want deeper SEO for each linked page, create dedicated landing pages per URL with unique metadata and share them from this repo or a subfolder.

## License

You may use and modify these files freely. No warranty — use at your own responsibility.

---
Created for quick GitHub Pages deployment.
