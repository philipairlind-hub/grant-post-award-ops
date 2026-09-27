# Grant Post-Award Ops

Public website for a founder-led post-award control setup for UK grant-making charities, foundations and professional foundation administrators.

Canonical offer: 7-day post-award control setup, £290 one-time for up to 60 active grants (administrator setup for up to 5 client portfolios: £490). The canonical offer text lives in `uk-grant-prospecting/docs/OFFER.md`; keep this site, the terms and the Stripe payment links consistent with it.

`example/` holds a fully synthetic example deliverable built by the fulfilment kit from a deliberately messy 20-row spreadsheet.

## Local preview

Serve the repository root with any static web server, for example:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Hosting

The site is designed for GitHub Pages and requires no build step or runtime dependencies.
