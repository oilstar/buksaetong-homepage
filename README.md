# Buksaetong Company Site

Static website for `buksaetong.com`.

## Pages

- `/` - official company homepage with e-commerce reselling and HAGOPA Studio branches
- `/HAGOPAStudio/` - game division homepage and expandable game catalog
- `/HAGOPAStudio/mooncrop/` - Mooncrop product page
- `/HAGOPAStudio/mooncrop/privacy.html` - Mooncrop privacy policy
- `/HAGOPAStudio/mooncrop/support.html` - Mooncrop support page
- `/HAGOPAStudio/sand-caravan/` - Sand Caravan product page
- `/HAGOPAStudio/sand-caravan/privacy.html` - Sand Caravan privacy policy
- `/HAGOPAStudio/sand-caravan/support.html` - Sand Caravan support page

## Game Catalog

Add new HAGOPA Studio games to `HAGOPAStudio/games.js`. Each catalog entry points to its own product,
privacy, and support pages, so the game section can grow without rewriting the studio homepage layout.

## Play Console URLs

- Official company website: `https://buksaetong.com/`
- HAGOPA Studio website: `https://buksaetong.com/HAGOPAStudio/`
- Mooncrop Privacy Policy: `https://buksaetong.com/HAGOPAStudio/mooncrop/privacy.html`
- Mooncrop Support: `https://buksaetong.com/HAGOPAStudio/mooncrop/support.html`
- Sand Caravan Privacy Policy: `https://buksaetong.com/HAGOPAStudio/sand-caravan/privacy.html`
- Sand Caravan Support: `https://buksaetong.com/HAGOPAStudio/sand-caravan/support.html`

## Deployment Notes

This site is deployed with GitHub Pages from the `main` branch root.

Keep the `CNAME` file set to `buksaetong.com`. In Squarespace DNS, point the root domain to GitHub Pages
with the four GitHub Pages A records and point `www` to `oilstar.github.io`.

Keep Google Workspace DNS records in Squarespace so `@buksaetong.com` email continues to work.
