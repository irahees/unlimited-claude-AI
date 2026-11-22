# Install the app on Android

This repository now includes a Progressive Web App (PWA) shell around the existing Claude-style chat page.

## Enable hosting

1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment → Source**, select **GitHub Actions**.
3. Open the **Actions** tab and run **Deploy PWA to GitHub Pages** if it does not start automatically after the next push.
4. When the workflow succeeds, open the published Pages URL in Chrome on Android.

## Install on Samsung / Android

1. Open the published site in Google Chrome.
2. Open Chrome's ⋮ menu.
3. Choose **Install app** or **Add to Home screen**.
4. Confirm the installation.

## Notes

- The service worker caches the app shell and chat page after the first successful online visit. AI responses still require an internet connection.
- Puter.js authentication and usage are governed by Puter's own account terms, limits, and availability. This project does not promise unlimited Claude usage or bypass provider limits.
- The existing chat page and its Puter.js integration are preserved; the PWA layer adds install metadata, an app entry point, and offline shell caching.
