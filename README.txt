# J.A.R.V.I.S. PWA — Setup Guide

## Files
- `index.html` — Main app
- `manifest.json` — PWA configuration
- `sw.js` — Service worker (enables offline + install)
- `icons/` — App icons

## How to Install as an App

### Option 1: Host on GitHub Pages (Free, Easiest)
1. Create a free GitHub account at github.com
2. Create a new repository (e.g. `jarvis`)
3. Upload all these files to the repo
4. Go to Settings → Pages → Source: main branch
5. Your app is live at `https://yourusername.github.io/jarvis`
6. Open that URL in Chrome/Edge → click the install icon in the address bar

### Option 2: Host on Netlify (Free, Drag & Drop)
1. Go to netlify.com → sign up free
2. Drag the entire jarvis-pwa folder onto the Netlify dashboard
3. You get a live HTTPS URL instantly
4. Open in Chrome/Edge and install

### Option 3: Local Network (No hosting needed)
1. Install Node.js from nodejs.org
2. Open terminal in the jarvis-pwa folder
3. Run: `npx serve .`
4. Open the shown URL in Chrome
5. Install banner will appear

## Installing on Phone
- **Android (Chrome)**: Open the hosted URL → tap ⋮ menu → "Add to Home Screen"
- **iPhone (Safari)**: Open the hosted URL → tap Share → "Add to Home Screen"

## Notes
- PWA install requires HTTPS (GitHub Pages and Netlify both provide this)
- Your Anthropic API key is saved in the browser's local storage on device
- Voice recognition requires Chrome, Edge, or Safari
