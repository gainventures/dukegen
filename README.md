# DukeGEN website (dukegen.org)

Static, single-page site. No build step. Files:

- `index.html`: all content and structure
- `styles.css`: light theme, mobile-first, colors from the DukeGEN logo
- `assets/`: horizontal and stacked logos (PNG, from `Logos/`)
- `CNAME`: custom domain for GitHub Pages

## Publish (GitHub Pages)

1. Create a repo, copy this folder's contents into it, push to `main`.
2. Settings > Pages > Source: `main` branch, root folder.
3. Settings > Pages > Custom domain: `www.dukegen.org`, then tick "Enforce HTTPS".
4. DNS at the registrar: `www` CNAME to `<your-github-user>.github.io`. For the apex `dukegen.org`, add A records to GitHub's Pages IPs (185.199.108.153, .109.153, .110.153, .111.153) and redirect apex to www.

## Before going live: fill these in

- Contact email `hello@dukegen.org` is a placeholder. Replace it in `index.html` (3 places) with a real inbox.
- Co-chair LinkedIn links were on the old Google Site; add them back on the cards if wanted.
- Event calendar: add real upcoming events (date, place, registration link) to the Events section.
- Confirm the Found & Seek wording for Michele's card.

## Affiliation notice

The statement "not affiliated with Duke University or the Duke Alumni Association" appears in the hero, the FAQ, the footer, and the structured data. Keep it on every page you add.
