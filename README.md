# Forge Macrometer

A static nutrition calculator, ready for GitHub Pages. No backend or build step is required.

## Publish

1. Create a GitHub repository named `forge-macrometer`.
2. Upload the contents of this folder to the repository root, including `.github/workflows/pages.yml` and `.nojekyll`. Commit to `main`.
3. In **Settings → Pages → Build and deployment**, choose **GitHub Actions**.
4. Run **Actions → Deploy GitHub Pages → Run workflow**, or push a new commit.
5. After deployment succeeds, open the URL shown in the workflow. For the `zaruto` account, the expected URL is `https://zaruto.github.io/forge-macrometer/`.

Alternatively, upload `index.html` and `.nojekyll`, then choose **Deploy from a branch**, branch `main`, folder `/ (root)` under Pages settings.

## Local preview

Run `python3 -m http.server 8080` in this folder and open `http://localhost:8080`.

## Behavior

The original design and calculator are preserved. Fat loss, maintenance, and bulk use bodyweight-based formulas. Height and age are displayed but do not affect calorie calculations. Nothing is sent to a backend. Styling, fonts, and icons load from external CDNs, so an internet connection is required.
