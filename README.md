# Only Us

This repository currently ships a single-page app in `onlyus.html`.

## Cloudflare Pages deployment

To host this on Cloudflare Pages:

1. Push this repository to GitHub/GitLab.
2. In Cloudflare Dashboard, go to **Workers & Pages → Create application → Pages → Connect to Git**.
3. Select this repository.
4. Use these build settings:
   - **Framework preset:** None
   - **Build command:** *(leave empty)*
   - **Build output directory:** `/`
5. Deploy.

`index.html` is included to redirect the root URL to `onlyus.html`, so opening the site root works immediately after deploy.
