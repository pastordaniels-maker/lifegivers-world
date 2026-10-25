# LifeGivers’ World Digital Ministry App — V1.1

**Tagline:** Creating your world with Love and God’s Word.

A responsive React + Vite ministry experience for daily scripture, devotional reflection, prayer requests, faith journaling, audio/worship discovery, and community pathways.

## Run locally

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
npm run preview
```

## Netlify

This repository includes `netlify.toml`. Set the build command to `npm run build` and the publish directory to `dist` if prompted. The app uses client-side routing/state, so the included redirect keeps page refreshes working.

## Notes

Prayer requests, journal entries, and devotional completion currently use browser local storage on the current device. They are not synced to an account or shared with ministry administrators. Audio, events, authentication, giving, notifications, and a ministry admin backend require their corresponding service integrations before production use.
