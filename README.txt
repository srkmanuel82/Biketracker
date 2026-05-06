# Bike Tracker PWA — Install Instructions

## What's included
- index.html    — The full app
- manifest.json — Makes it installable as an app
- sw.js         — Service worker (offline support)
- icons/        — App icons

## How to install on your phone

### Option 1: Use a free hosting service (easiest)

1. Go to https://app.netlify.com/drop
2. Drag the entire `biketracker` folder onto the page
3. Netlify gives you a live URL (e.g. https://abc123.netlify.app)
4. Open that URL in Chrome on your Android phone
5. Tap the "Install" banner that appears, or tap ⋮ → "Add to Home Screen"
6. The app icon appears on your home screen — tap it to open like a real app!

### Option 2: GitHub Pages (free, permanent)

1. Create a free account at github.com
2. Create a new repository called `bike-tracker`
3. Upload all files from this folder
4. Go to Settings → Pages → Source: main branch
5. Your app is live at https://yourusername.github.io/bike-tracker
6. Open on your phone and install from Chrome

### Option 3: Local Wi-Fi (no internet needed)

1. Install Python (python.org)
2. Open terminal in this folder and run:
   python3 -m http.server 8080
3. Find your computer's local IP (e.g. 192.168.1.5)
4. On your phone (same Wi-Fi), open Chrome and go to:
   http://192.168.1.5:8080
5. Tap ⋮ → "Add to Home Screen"

## Features
- Live heart rate tracking via Polar Bluetooth HRM
- Heart rate zones (Z1–Z5) with % max HR bar
- Calorie calculation using your age, weight, and HR
- Norwegian 4x4, interval, steady ride, and more workout types
- Workout history saved on your device
- Works offline after first load
- Dark mode, mobile-optimized UI

## Notes
- Web Bluetooth requires Chrome or Edge on Android (not Safari/iOS)
- On iPhone, Bluetooth HRM won't connect but everything else works
- Your workout history is saved in your browser's local storage
