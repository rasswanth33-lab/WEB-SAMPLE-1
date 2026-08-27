# cinematic-director-46

Static snapshot of https://cinematic-director-46.aura.build

It is a client-side React app. Serve the folder over HTTP (not `file://`):

```
python -m http.server 8000
# open http://localhost:8000/
```

Images load from a public Supabase bucket and fonts from Google Fonts, so an
internet connection is still needed for full rendering. Routing uses a hash
router, so any static host (GitHub Pages, Netlify, Vercel) works with no extra
config.
