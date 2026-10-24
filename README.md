# Solo System PWA

A free, personal Solo Leveling-inspired RPG tracker.

## Included
- Dashboard with XP, level, rank, streak, daily progress
- Quest board with core quests and custom side quests
- Workout split template and session logging
- 66-day episode campaign and boss challenges
- Six-stat diamond/radar chart
- Local browser storage and JSON export/import
- PWA manifest and service worker for install/offline support

## Run locally
Opening `index.html` directly works for basic use and local saves, but PWA installation/offline caching require serving over HTTPS or localhost.

### Easy local preview
If Python is installed:
`python -m http.server 8000`
Then open `http://localhost:8000` in your browser.

### Install on Android
1. Host the folder on a free static host that provides HTTPS (for example, a free GitHub Pages site), or serve it from a computer on a secure development setup.
2. Open the HTTPS site in Chrome.
3. Use Chrome menu → Add to Home screen / Install app.

### Install on desktop
Open the HTTPS site in Chrome or Edge and use the install icon/menu.

## Important notes
- Saves are local to each browser/device. They do not sync automatically between phone and laptop.
- Export a JSON backup regularly and import it on another device if needed.
- This is a starter template. The workout split is generic and should be customized for your equipment, experience, schedule, and any injuries.
- No paid service or subscription is required to run the app. A public hosting provider may have its own terms and free-tier limits.
