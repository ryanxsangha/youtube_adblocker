# YouTube Ad Blocker (Browser Extension)

A lightweight browser extension that blocks YouTube ads using network request filtering.

## Features

- Blocks video ads, mid-roll ads, and ad trackers on YouTube
- Uses `declarativeNetRequest` (Manifest V3)
- Compatible with Chrome and Firefox (with partial support)

## How It Works

The extension blocks known ad-serving URLs and YouTube ad endpoints using static rules (`rules.json`).

## Installation

### Chrome
1. Go to `chrome://extensions`
2. Enable **Developer mode**
3. Click **"Load unpacked"**
4. Select the `youtube_adblocker` folder

### Firefox
1. Go to `about:debugging#/runtime/this-firefox`
2. Click **"Load Temporary Add-on…"**
3. Select the `manifest.json` file

## Files

- `manifest.json` – Extension manifest
- `rules.json` – List of blocked ad URLs
- `content.js` (optional) – Skips DOM-based overlay ads

## Disclaimer

This extension is for educational purposes only. YouTube may change ad behavior at any time.

