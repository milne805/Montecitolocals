# Montecito Locals
Mobile-first local discovery app for 93108: happy hours, specials, live music and local events.

## Publish at montecitolocals.com with GitHub Pages
1. Create a GitHub repository and upload the contents of this folder to the repository root.
2. Settings → Pages → Deploy from branch → main / root.
3. In Pages, set Custom domain to `montecitolocals.com` (the included CNAME file already contains it).
4. At your domain registrar, point DNS to GitHub Pages according to GitHub's current custom-domain instructions, then enable HTTPS after DNS verifies.

## Data
`deals.json` is the content feed. Every item contains a source URL and is intended to be verified against current venue/local sources.
