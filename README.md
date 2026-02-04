# Solar Panel Maximum Power Point Analysis

Interactive data visualization for solar panel experiments measuring voltage, current, and power across varying load resistances to identify the maximum power point (MPP).

## Overview

Two experiments compare solar cell performance under different source configurations:

- **Experiment 1** -- 30 V source
- **Experiment 2** -- 29 V PSU @ 0.8 A

Each experiment plots voltage, current, and power vs. load resistance, with a comparison view showing both datasets overlaid.

## Key Result

Both experiments confirm the **Maximum Power Transfer Theorem**: peak power delivery occurs when the load resistance matches the solar panel's internal resistance (~16--20 &Omega;), regardless of illumination intensity.

## Tech

Single-file static page. No build step.

- [Chart.js](https://www.chartjs.org/) for plots
- CSS custom properties for light/dark theming
- Google Fonts (Inter)

## Deploy

### Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/project)

Push to GitHub, then import the repo in the Vercel dashboard. No configuration needed -- Vercel will serve `index.html` as-is.

### Any static host

Upload `index.html` to any static hosting provider (GitHub Pages, Netlify, Cloudflare Pages, etc.).

## License

MIT
