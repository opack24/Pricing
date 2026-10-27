# FoldMate Competitive Pricing Intelligence Dashboard

A responsive, interactive static dashboard built from the Mission 1 competitive-pricing research snapshot. It presents five competitors and all 18 researched price records, with transparent treatment of different pricing units and research limitations.

## Run locally

Serve this folder with any static HTTP server and open its root URL. The dashboard loads `competitor_data.json` at runtime; it does not require a backend, API key, or build step.

## Data

`competitor_data.json` is the primary research dataset. It is based on the supplied Mission 1 workbook and report, with official source URLs and a research date of October 27, 2026. Price and availability observations are snapshots, not live feeds. The dashboard does not estimate demand, revenue, margin, or willingness to pay.

## GitHub Pages

This project is published from the `main` branch root. In the repository, enable Pages with **Settings → Pages → Build and deployment → Source: Deploy from a branch**, then select **main** and **/(root)**. No build or backend is required.

## Technology

Semantic HTML, CSS, and vanilla JavaScript with SVG charts. No external runtime libraries are needed. Typography uses Google Fonts when network access is available and falls back to system sans-serif fonts otherwise.
