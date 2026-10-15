SachCheck V4 — Website + installable PWA starter
=================================================

Included:
- index.html: SachCheck V3 features (message rules, screenshot OCR attempt, URL-format checks)
- manifest.json: installable web app metadata
- sw.js: basic service worker for caching
- README.txt: mobile deployment guide

Important:
- This is a website/PWA starter, NOT an APK and NOT ready for Google Play Store.
- To install as a home-screen app, host the files on an HTTPS website first.
- Screenshot OCR loads Tesseract.js from a CDN and requires internet.
- AI analysis and live URL reputation lookup are not connected yet.
- Never put API keys in frontend HTML. For real AI/live reputation services, a backend/proxy is needed.
- Do not paste OTPs, passwords, bank details, or sensitive personal messages.
- Low warning signals do not mean a message or link is safe.

Android phone next steps:
1. Extract this ZIP.
2. Upload the files to an HTTPS static host (for example GitHub Pages or another static hosting service).
3. Open the hosted site in Chrome.
4. Use Chrome menu (⋮) > Install app / Add to Home screen if offered.
5. This creates an installable web app shortcut/PWA, not a Play Store APK.

A native APK or Play Store release needs a separate Android build/signing process.
