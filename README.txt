# AVR Dashboard Hub — installable PWA starter

## What this package does
- Preserves the AVR responsive HTML dashboard and existing local demo report/case logic.
- Adds web-app manifest, app icon, an Install AVR button, and a service worker for offline shell caching.
- Is suitable for hosting as a Progressive Web App (PWA) on an HTTPS site.

## Important limits
- The existing reports and case data are demo/local browser data, not shared online.
- Map markers remain simulated; the external map library may require internet access.
- No agency, police, towing, SMS/email, payment, or real-time GPS integrations are active.
- A service worker and browser install flow do not work by simply opening index.html from the phone's Downloads folder. Host the package on an HTTPS site first.

## Run locally for testing
From a computer with Python installed, open a terminal in this folder and run:
    python -m http.server 8000
Then open http://localhost:8000 in a browser. For installation on an Android phone, host on HTTPS and open the URL in Chrome.

## Android app route
This PWA can be wrapped for Android after testing, or the HTML can be loaded into an Android Studio WebView project. Google Play publishing requires a developer account and its current registration requirements; do not pay until you decide to publish.
