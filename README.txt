TARIADS PWA INSTALL TEST STARTER

Contents:
- index.html: empty install-test landing screen
- manifest.webmanifest: PWA name, launch URL, display mode, colors and icon declarations
- sw.js: basic offline app-shell caching
- icons/: 192px, 512px, maskable, Apple touch, favicon, and supplied wordmark

TEST ON ANDROID:
1. Upload the CONTENTS of this folder to a static HTTPS host such as Cloudflare Pages.
2. Open the deployed URL in Chrome on Android.
3. Wait for the page to finish loading; use Chrome menu > Install app / Add to Home screen.
4. Launch it from the home screen to see the standalone app appearance.

IMPORTANT:
- PWA installation requires HTTPS (localhost is the usual development exception).
- Keep index.html, manifest.webmanifest, sw.js, and icons/ at the same site root.
- This is only an install shell; it does not contain listings, login, search, or backend logic.
