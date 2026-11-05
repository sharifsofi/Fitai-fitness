FitAI iPhone install package

1. Upload this folder to a static HTTPS host (for example GitHub Pages, Netlify, or Vercel).
2. Open the hosted URL in Safari on your iPhone.
3. Tap Share -> Add to Home Screen -> Add.
4. Launch FitAI from the new Home Screen icon.

Important:
- iPhone does not reliably install/run a PWA directly from a local HTML file in Files.
- This package needs to be served over HTTPS for installation and offline caching.
- AI nutrition estimates and AI workout-plan generation need a working provider integration.
- Do not put a private API key directly into public client-side HTML. Use a secure backend/proxy.
