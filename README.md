# JEGOL Furniture — GitHub Pages deployment

## Files
- `index.html` — website homepage and catalog
- `jegol-image-01.webp`, etc. — local image assets used by the site

All image assets are in the same directory as `index.html`, so no build step or external image hosting is required.

## Deploy with GitHub Pages
1. Create or open a GitHub repository.
2. Upload `index.html` and every `jegol-image-*.webp` file to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your deployment branch (usually `main`) and folder `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site.

Keep the image files beside `index.html`; do not rename them unless you also update the references in `index.html`.

The existing catalog content and contact information have been preserved.
