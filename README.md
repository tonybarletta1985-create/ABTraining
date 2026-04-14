# AB Training — Gold Coast Half Marathon 2026

12-week half marathon training dashboard. Target: 1:35:00 · July 5, 2026.

---

## Install on iPhone (via GitHub Pages)

1. Go to **Settings → Pages** in your GitHub repo
2. Set Branch → main → / (root) → Save
3. Your URL: `https://YOURUSERNAME.github.io/REPONAME`
4. Open URL in **Safari** on iPhone
5. Tap **Share** → **Add to Home Screen** → **Add**

---

## Strava integration

After setting up GitHub Pages, update your Strava API settings at
**strava.com/settings/api**:

- Website → your GitHub Pages URL
- Authorization Callback Domain → `YOURUSERNAME.github.io`

Then tap **Connect Strava** in the Log Session tab to authorise.

---

## Files

```
ab-training/
├── index.html       ← Full training dashboard (all-in-one)
├── manifest.json    ← PWA config
├── sw.js            ← Offline service worker
└── icons/
    ├── icon-152.png
    ├── icon-167.png
    ├── icon-180.png
    ├── icon-192.png
    └── icon-512.png
```

## Data & privacy

All session data is stored in your browser's localStorage — nothing
is sent to any server. Strava data is fetched directly from the
Strava API to your browser only.
