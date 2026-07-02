Wayland Square Connect TEST v32 - App Icon Badge Sync

Web files:
- Upload index.html, firebase-messaging-sw.js, and manifest.webmanifest to the TEST GitHub repo.

Functions files:
- Copy the four files inside the functions folder into C:\WaylandSquareConnect\functions.
- Replace index.js, notificationEngine.js, notificationTemplates.js, and package.json.
- Then run:
  cd C:\WaylandSquareConnect\functions
  npm install
  cd C:\WaylandSquareConnect
  firebase deploy --only functions

This build adds server badge counts to chat push notifications and app-side badge clearing when alerts are read.
Deployment refresh – July 2, 2026
