# Williamson UK Trip — PWA Itinerary

Your complete family itinerary for April 14–20, 2026 (London → Manchester).

## Deploy to Vercel (2 minutes)

### Option A: Vercel CLI (if you have it installed)
```bash
cd williamson-trip
vercel
```
Follow the prompts. Done!

### Option B: Vercel Dashboard (drag & drop)
1. Go to https://vercel.com/dashboard
2. Click **"Add New" → "Project"**
3. Click **"Import Third-Party Git Repository"** or just drag the `williamson-trip` folder onto the page
4. Or: Push this folder to a GitHub repo and import from there
5. Vercel auto-detects it as a static site — just click **Deploy**

### Option C: Push to GitHub first
```bash
cd williamson-trip
git init
git add .
git commit -m "UK trip itinerary PWA"
gh repo create williamson-uk-trip --public --push
```
Then import the repo in Vercel.

## Add to Home Screen (iPhone)

Once deployed (e.g. at `https://williamson-uk-trip.vercel.app`):

1. Open the URL in **Safari** on your iPhone
2. Tap the **Share button** (square with arrow)
3. Scroll down and tap **"Add to Home Screen"**
4. Name it "UK Trip" and tap **Add**

It now works like a native app — full screen, no Safari chrome, and works offline!

## Features
- 📱 PWA — works as a standalone app on iPhone/Android
- 📍 Google Maps links for every day's route
- ⏰ Hour-by-hour timeline with transit details
- 👆 Swipe left/right to navigate between days
- 📶 Works offline after first load
- 🎨 Dark theme, mobile-optimized
