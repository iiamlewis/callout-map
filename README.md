# callout-map

Static live-location page for the Call-Out app. Source of truth is `server/map.html` in the private Call-Out repo; this repo only hosts it on GitHub Pages.

The key in `config.js` is the Supabase publishable key, which is public by design: with row-level security on and no policies it can only call the four RPC functions.
