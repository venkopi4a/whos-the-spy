# Who's the Spy 🕵️

A pass-and-play party game for 4–8 friends on one phone. One secret place. Someone's lying.

## Put it online (GitHub Pages)

1. Create a new **public** repository on GitHub, e.g. `whos-the-spy`.
2. Click **Add file → Upload files** and drag in **all files from this folder** (they must sit at the top level of the repo, not inside a subfolder). Commit.
3. Go to **Settings → Pages**. Under *Build and deployment*, set **Source: Deploy from a branch**, **Branch: main**, folder **/ (root)**. Save.
4. Wait 1–2 minutes. Your game is live at `https://<your-username>.github.io/<repo-name>/`.

## Install it like an app

- **Android (Chrome):** open the site and tap **📲 Install the app** on the home screen of the game.
- **iPhone (Safari):** tap **📲 Install the app** for instructions, or Share ⬆️ → **Add to Home Screen**.

Once installed it opens full screen with its own icon and works offline.

## Updating the game

1. Upload the new `index.html` (replace the old one).
2. Open `sw.js` and change `VERSION = "spy-v2"` to the next number (`spy-v3`, `spy-v4`…). Commit.
3. Installed phones get the update the next time they open the game while online.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole game |
| `manifest.webmanifest` | App name, colours and icons for installing |
| `sw.js` | Offline support |
| `icon-*.png`, `apple-touch-icon.png`, `favicon.png` | App icons |
| `.nojekyll` | Tells GitHub Pages to serve files as they are |
