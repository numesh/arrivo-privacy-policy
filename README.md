# Arrivo – Privacy Policy Website

A simple, professional, single-page privacy policy website for the **Arrivo** Android app. Hosted via GitHub Pages.

## About Arrivo

Arrivo is a proximity-based arrival alert app that notifies users when they approach a selected destination. It uses fine/background location, Google Places API, OSRM routing, Firebase Remote Config, and Google AdMob — all without collecting personal user data.

## Project Structure

```
arrivo-privacy-policy/
├── index.html          # Main (and only) page — the privacy policy
└── .github/
    └── copilot-instructions.md
```

## Deploying to GitHub Pages

1. Push this repository to GitHub.
2. Go to your repository **Settings → Pages**.
3. Under **Source**, select the branch (e.g. `main`) and set the folder to `/ (root)`.
4. Click **Save**. GitHub Pages will publish the site at:
   ```
   https://<your-username>.github.io/<repo-name>/
   ```

## Editing the Policy

- Open `index.html` in any text editor.
- Update the **Last Updated** date at the top of the file when making changes.
- All styles are inside the `<style>` tag — no external CSS files.
- No build step required. Changes are live as soon as they are pushed to GitHub.

## Requirements Met

- ✅ Pure HTML + CSS (no frameworks)
- ✅ Responsive / mobile-friendly
- ✅ Max 800px centered layout
- ✅ System font stack (no web fonts)
- ✅ Google Play Store privacy policy compliant
- ✅ GitHub Pages compatible (single `index.html`)
- ✅ No external dependencies
