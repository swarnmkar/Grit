GRIT — SETUP GUIDE (Phone install via GitHub Pages)
=====================================================

Same process you used for Reclaim. About 5 minutes, once.
After that: tap the icon on your home screen, done.


WHAT YOU NEED
--------------
- A free GitHub account (github.com)
- Your phone (Android or iPhone)


STEP 1 — Create a new repository
-----------------------------------
1. Go to github.com → sign in
2. Tap the "+" or "New" button → New repository
3. Repository name: grit  (or any name you like)
4. Set it to Public
5. Create repository


STEP 2 — Upload the app files
-------------------------------
1. In Chrome, tap ⋮ → "Desktop site" (this reveals the upload option)
2. On the repo page: "Add file" → "Upload files"
3. Upload ALL 5 files from this folder:
     index.html
     manifest.json
     sw.js
     icon-192.png
     icon-512.png
4. Scroll down → "Commit changes"


STEP 3 — Enable GitHub Pages
-------------------------------
1. Still in desktop mode: go to Settings → Pages (left sidebar)
2. Source: Deploy from a branch
3. Branch: main  |  Folder: / (root)
4. Save
5. Wait 1-2 minutes — the live URL appears at the top of that page:
     https://YOUR-USERNAME.github.io/grit


STEP 4 — Install on your phone
---------------------------------
Open that URL on your phone:

Android (Chrome):
  ⋮ → "Add to Home Screen" (or accept the banner Chrome shows)

iPhone (Safari — must use Safari, not Chrome):
  Share button (□↑) → "Add to Home Screen"

The Grit icon appears on your home screen. Tap it — fullscreen,
no browser bar, works fully offline.


YOUR DATA
----------
All training data stays in your phone's browser storage.
GitHub only hosts the app code — no personal data ever
leaves your device.

Use Export (You tab) to back up your data as a JSON file
periodically. If you ever clear your browser's site data,
use Import to restore it.


UPDATING THE APP LATER
-------------------------
If you get an updated index.html from me:
1. Go to your repo on GitHub (desktop mode)
2. Click index.html → pencil icon (Edit) → select all, paste new
   code → Commit
   (or just drag-drop the new file to replace it)
3. Open the app on your phone, fully close it and reopen
   (swipe away from recent apps first) — the new code loads
   automatically thanks to the service worker's update check.
