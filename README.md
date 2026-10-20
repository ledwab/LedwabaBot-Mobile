# LedwabaBot Android dashboard starter

This is a mobile-first Progressive Web App (PWA) starter for the LedwabaBot project.

## What works now
- Responsive Android-friendly dashboard
- XAUUSD workspace and connection checklist
- Local-only preferences for symbol, risk setting, and operating mode
- Installable PWA support when hosted over HTTPS

## What does not work yet
- No live price feed
- No connection to MetaTrader 5
- No trade execution
- Start/Stop controls are intentionally disabled

## How to preview
Open `index.html` in a browser for a basic preview. To install it like an app, host the folder on an HTTPS site (for example GitHub Pages), then open the site in Chrome on Android and use the browser menu's "Add to Home screen" or "Install app" option if available.

## Next development step
Build a secured backend service that runs on the Windows PC/server alongside MT5. The Android dashboard should communicate with it using authenticated HTTPS/WebSocket requests. Never put broker passwords or API secrets in frontend files. Test in demo mode before enabling any live-trading functionality.
