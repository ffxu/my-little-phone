Tiny Phone Adventures
=====================

Files
-----
- index.html: the complete app and its eight activities
- manifest.webmanifest: installable web-app metadata
- sw.js: offline caching service worker
- README.txt: these instructions

Publish on the existing GitHub Pages site
------------------------------------------
1. Open the existing repository: https://github.com/ffxu/my-little-phone
2. Upload/replace index.html, manifest.webmanifest, and sw.js in the same published folder.
3. Commit the changes.
4. Wait for GitHub Pages to publish, then open https://ffxu.github.io/my-little-phone/
5. If an installed iPhone shortcut still shows the old version, close it fully and reopen after the service worker refreshes. If needed, remove and re-add the home-screen shortcut.

Parent setup
------------
- The parent area is hidden in the bottom-left corner. Press and hold for about 3 seconds.
- On first use, create a 4-digit parent PIN.
- Later, enter that PIN to change the child's nickname, change the PIN, or clear the nickname.
- The child's nickname and parent PIN are stored locally in that browser/device. They are not sent to a server.
- If browser/site data is cleared, local personalization and PIN are also cleared.

Important notes
---------------
- This is a static web app. It does not create child accounts or collect names on a server.
- The website is publicly accessible to anyone with the URL.
- A website cannot fully block iOS system gestures. For stronger kiosk-style protection, use iPhone Guided Access.
- This first implementation uses built-in emoji and CSS illustrations, so it does not download external image assets.
- The games are designed as simple, forgiving toddler activities. Test on the target iPhone before sharing widely.
