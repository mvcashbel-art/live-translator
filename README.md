# Live Translator

Speak or type and get a live translation. English and Bisaya (Cebuano) are auto-detected and translated to each other. Includes a full-screen caption view and a display window for a projector or TV.

**Live page:** https://mvcashbel-art.github.io/live-translator/

## Files
- `index.html` – the whole app (single file).
- `cloud-token-service.gs` – Google Apps Script that hands the page a short-lived ElevenLabs token, so the secret API key never sits in the web page. Only needed for the **Cloud mic** (hears Bisaya + English mixed).

## Use
1. Open the live page in Chrome or Edge and tap the mic. The free **Browser mic** hears one language at a time (English or Filipino).
2. For mixed Bisaya + English, set up the Cloud mic: follow the comments at the top of `cloud-token-service.gs`, then paste the web app URL into the page under **Cloud mic setup**.
3. **Full-screen captions** shows only the translation. **Display window** opens a second window to drag onto a projector.

Translation is machine-generated; double-check anything important.
