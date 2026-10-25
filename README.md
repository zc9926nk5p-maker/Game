# Pocket Pitch

A personal Pokémon football management game. Single page, no build step.

## Put it on your iPhone with GitHub Pages

1. On github.com, create a new repository (for example `pocket-pitch`). Public is required for free GitHub Pages; private works on paid plans.
2. Click **Add file → Upload files** and drag in everything in this folder, including the `sprites` folder. Commit.
3. Go to **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
4. After a minute or two your game is live at `https://<your-username>.github.io/pocket-pitch/`.
5. On your iPhone, open that link in **Safari**, tap **Share → Add to Home Screen**. It launches full screen like an app.

## Save slots

You can run up to 3 franchises side by side. After logging in, pick one from "Your franchises", or switch any time from Club → Settings → Switch franchise. Each save code (Club → Settings) covers the franchise you have open.

## Bring your current franchise over

In the version you've been playing, open **Club → Settings** and copy the save code. In the GitHub version, paste it into **Load save**.

## Adding sprites

Drop PNG files into `sprites/`, named as listed in `sprites/FILENAMES.txt` (for example `pikachu.png`, `mr-mime.png`, `farfetchd.png`). Upload them to the repo the same way. As soon as `sprites/bulbasaur.png` exists, the game shows sprites on the pitch, in the pickers and in the draft feed. Any Pokémon without a file keeps its type emblem.

## Updating the game later

Upload a new `index.html` over the old one. Your saves live on your phone, so they carry over.
