# 009 storefront — recovered source (clean src was lost; this de-minified bundle is the working source)
- `storefront.deminified.js` — readable de-minified React bundle (js-beautify). EDIT HERE, then:
  `npx esbuild _source/storefront.deminified.js --minify --format=esm --outfile=assets/index-<hash>.js`
- `overrides.css` — appended CSS overrides (Gleb edits 2026-08-12). Deployed CSS = original base CSS + this file.
- After building, update the `index-*.js` / `index-*.css` hashes in `index.html`.
- Backend: PocketBase `009-merch-backend-production.up.railway.app`; images: Cloudinary.
