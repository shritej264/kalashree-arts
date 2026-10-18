# Kalashree Arts — starter website

A responsive, single-page starter website for Kalashree Arts. It includes sample handmade rangoli artwork (original SVG illustrations), sample product cards, WhatsApp Buy Now links, a live-class demo section, free recorded-lesson placeholders, and a browser-only admin demo.

## Run it locally
1. Download and unzip this folder.
2. Open `index.html` in Chrome, Edge, or Firefox.
3. Replace sample product names/prices and WhatsApp number if needed.

## Important before launch
- The live classroom currently supports a local camera/mic preview and on/off controls. It does NOT connect separate students/teacher over the internet yet. For a real multi-person room, integrate LiveKit with a secure server-side token endpoint.
- The admin demo is NOT secure and saves to localStorage in one browser only. Do not use it for real business administration or sensitive information.
- Recorded lessons are placeholders. Add public video URLs to the `data-video` attributes in `index.html`.
- Product photos are original SVG sample illustrations; replace them with real product photos when ready.
- This is a static front-end prototype. A production version needs a real authentication system, database, secure admin roles, server-side API, and live-video integration (for example LiveKit or Cloudflare Stream).
- GitHub Pages is designed for static sites and has restrictions around commercial e-commerce use. For a business launch, check current GitHub Pages terms and consider suitable commercial hosting.
- The sample prices are illustrative only. Confirm actual prices, shipping, availability and policies before publishing.

## WhatsApp
Current number: `917875544991` (international format without `+`).
Search `917875544991` in `index.html` to change it.

## Suggested next development phase
1. Create a Next.js project.
2. Add Supabase authentication and database.
3. Add a secure admin area.
4. Integrate LiveKit (two-way teacher/student camera and mic) with a secure token endpoint, then test with 5, 30, and 100 participants.
5. Set up video storage/recordings and public replay pages.
