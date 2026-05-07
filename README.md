# midas-buy-front

Static UI for the [midasbuy-hybrid](https://github.com/medcharaf111/midasbuy-hybrid)
player-ID lookup service. Single `index.html`, no build step. Calls the Railway
daemon via the `API` constant near the top of the script tag — change it there
if the backend URL changes.

## Deploy on Vercel

1. Connect this repo to a new Vercel project.
2. Vercel auto-detects a static site and deploys `index.html` at the root.
3. No build command, no output directory, no env vars needed.

## Local preview

Any static server works:

```
npx serve .
# or
python -m http.server 8000
```

Then open http://localhost:8000.
