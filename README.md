# ECO-SMART

Smart Waste Segregation, Disposal and Sanitization Platform — Smart India Hackathon 2026.

## GitHub Pages

1. Create a **Public** GitHub repository named `ECO-SMART`.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then **Save**.
6. Wait for GitHub Pages to publish the site.

## Important

This version is prepared for static GitHub Pages hosting:
- The page is renamed to `index.html`.
- VS Code Live Preview injected code is removed.
- Chart.js uses a public CDN.
- The local Google Fonts cache reference is replaced with the Google Fonts URL.
- Local VS Code navigation URLs are replaced with normal page anchors.

The current **Report Waste** submission and AI analysis in the HTML are frontend/browser-side simulations. They do **not** directly save reports to MySQL. For MySQL/Flask integration, the page must be connected to a separately hosted backend.
