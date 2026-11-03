# Leaf It To Me

An offline-first lists and notes web app (installable on a phone home screen).

- Lists and items are saved on the phone (localStorage), so the app opens and works with no signal.
- Optional sync: the app keeps one `data.json` file in the private `Leaf-data` repo using a GitHub access token that is pasted into the app once. The token is stored only on the phone, never in this repo.
- This repo holds only the app code. It contains no personal data, so it can be public (free GitHub Pages).

Files: `index.html` (the whole app), `sw.js` (offline cache), `manifest.webmanifest`, icons.
After the app code changes, open the app twice to pick up the new version (the offline cache refreshes in the background).
