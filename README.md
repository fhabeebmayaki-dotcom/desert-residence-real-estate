# Desert Residence — Luxury Real Estate One-Pager (Scroll-Controlled Hero)

A warm, editorial one-pager for a single luxury listing, inspired by the "Desert Residence" scroll-experience sites: the visitor scrolls and the camera glides through the home — terrace, pool, glass walls, great room — while the headline evolves with each view.

## What's inside
- **Scroll-controlled cinematic hero** — sticky stage, scroll scrubs through 4 architectural photos with a continuous Z-axis dolly-zoom and crossfades; evolving serif headlines, price card, numbered stage buttons and a vertical progress track.
- **Specs strip** — beds, baths, living area, lot, pool length, year built.
- **Story section** — listing narrative with an 8-item feature list.
- **Gallery with lightbox** — 6 captioned photos, full-screen viewer with prev/next buttons and keyboard arrows.
- **Floor plan & spaces** — two interior studies plus an itemised space/area table that totals to the advertised square footage.
- **Agent card** — photo, bio quote, contact and sales stats beside the tour form.
- **Private-tour request form** — validation (name, email, phone, future date, party size), optional notes field, and a personalised confirmation state.
- Scroll-reveal animations throughout; fully responsive.

## Customise it for a buyer
- **Listing details:** price and address are in the hero price card; specs strip numbers are plain HTML; the space table is a simple `<table>` — keep the total row consistent.
- **Photos:** replace files in `images/` — hero stages `hero-1.jpg` … `hero-4.jpg`, gallery `gallery-1.jpg` … `gallery-6.jpg`, interiors `plan-dining.jpg` / `plan-living.jpg`, broker portrait `agent.jpg`.
- **Headlines:** each hero stage's copy is a `.slide` block in the hero — edit text freely, keep 4 slides to match the 4 stages.
- **Branding:** agent name/agency in the Agent card, `--acc` terracotta variable for the accent colour.

## Tech
Single self-contained `index.html` (embedded CSS + vanilla JS), local images only, no build step, no external requests. Works on any static host (GitHub Pages, Netlify, Vercel).

Photos: Unsplash (free to use). Demo content — property details and price are illustrative.
