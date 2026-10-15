MY HABIT SPACE - PWA (GitHub Pages compatible)

Upload ALL files and the icons folder to the ROOT of your GitHub repository.
Required files:
- index.html
- app.js
- styles.css
- manifest.webmanifest
- service-worker.js
- icons/icon-192.png
- icons/icon-512.png

GitHub Pages:
Settings > Pages > Deploy from a branch > main > /(root)

After updating an older deployment:
1. Wait until GitHub Pages reports the deployment finished.
2. On Android Chrome, close the old tab completely.
3. Open the GitHub Pages URL again.
4. Refresh once.
5. If an old shortcut exists, remove that shortcut before testing installation.
6. Look for the Install button inside the app or Chrome menu > Install app.

Your habit data stays in browser/device local storage. Updating these app files does not normally erase that data as long as the same GitHub Pages URL/origin is used.
