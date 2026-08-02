# Support Calculator v2.1 — Stage 8 PWA

All files sit at the repository root. There is no sub-folder, so every file
can be uploaded to GitHub in one drag-and-drop.

## Files (8, flat)

```
index.html
manifest.webmanifest
service-worker.js
icon-192.png
icon-512.png
icon-maskable-192.png
icon-maskable-512.png
apple-touch-icon.png
```

## Upload

1. Open the repository on github.com
2. **Add file → Upload files**
3. Select all 8 files together (Ctrl+A in the file picker) and drop them in
4. **Commit changes**
5. **Settings → Pages →** Source: `Deploy from a branch`, Branch: `main` / `/ (root)`

## Install on Android

Open the Pages URL in Chrome, refresh once, then **⋮ → Install app / Add to Home screen**.

If an older version was opened before, clear the site data or unregister the old
service worker, then reload. The cache name is bumped each release.

## What changed in v2.1

- Fixed unescaped `</script>` that stopped all JavaScript from running
- Added the missing `#drawingSummary` element
- Shear stress now uses the web shear area `Av`, not the gross area `A`
- Beam self-weight included as a uniformly distributed load (toggle)
- Angle section moduli recomputed from the true centroid
- Cold-formed strut properties flagged with an effective-section factor
