# HSTC Fuel Dashboard Demo

A simple HTML dashboard demo for HSTC fleet fuel analytics.  
This repo is meant to be easy to edit and iterate on using AI agents.

## What’s inside
- A static dashboard page (HTML) that can be opened directly in a browser.
- No build step, no dependencies.

## Quick start
### Option 1: Open locally
1. Download or clone this repo.
2. Open the HTML file in your browser.

If you renamed the file to `index.html`, just open `index.html`.  
If you kept the original name, open `HSTC_Fleet_Fuel_Analytics (2).html`.

### Option 2: Use GitHub Pages (optional)
If you want a public link:
1. Go to **Settings → Pages**
2. **Source**: Deploy from a branch
3. **Branch**: `main` and folder `/ (root)`
4. Save

Tip: GitHub Pages loads `index.html` by default, so renaming the HTML file to `index.html` is recommended.

## Editing workflow (AI-friendly)
Recommended structure if you expand the project:
- `index.html`
- `assets/` (images like logos)
- `css/` (styles)
- `js/` (scripts)

If the logo is embedded in the HTML (Base64), nothing else is required.  
If you prefer using a real image file, put it in `assets/logo.png` and update the `<img src="...">` accordingly.

## Notes
- Keep changes small and incremental.
- When testing, refresh the page (hard refresh if needed).
