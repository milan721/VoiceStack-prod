Deployment notes

- Added `index.html` which redirects to `code.html` so static hosts (GitHub Pages, Netlify, etc.) will serve the page by default.
- Removed external Google Fonts from `code.html` and added an inline SVG favicon to avoid common 404 requests for external assets.

How to deploy (GitHub Pages):

1. Commit and push the repository to GitHub.
2. In the repository settings, enable GitHub Pages and select the `master` (or `main`) branch and the `/ (root)` folder.
3. Your site will be available at `https://<your-org-or-user>.github.io/<repo>/`.

If you use a different host (Netlify/Vercel), point the publish directory to the repository root or follow the host's instructions.

If you still see a 404, open your browser DevTools → Network and share the failing request URL and its initiator so I can address it specifically.
