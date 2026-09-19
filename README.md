# phaneslabs.com

The public website for [Phanes Labs](https://phaneslabs.com) — a static,
dependency-free site deployed on Vercel.

## Pages

- `/` — landing page (links to the app at [app.phaneslabs.com](https://app.phaneslabs.com))
- `/privacy` — privacy policy
- `/terms` — terms of service
- `/imprint` — Impressum (legal notice)
- `/support` — support & contact

## Development

Plain HTML + CSS, no build step. Open `index.html` in a browser, or:

```bash
npx serve .
```

`vercel.json` enables `cleanUrls`, so `/privacy` serves `privacy.html` in
production.

## Deployment

Pushes to `master` deploy automatically via Vercel.
