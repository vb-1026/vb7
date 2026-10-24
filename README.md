# Viloyatga Boramiz — improved interactive prototype

## Run
1. Open `index.html` in a modern browser.
2. Keep an internet connection for OpenStreetMap tiles, address lookup, and OSRM route estimates.
3. For device location, use HTTPS or localhost and grant browser location permission.

## Improvements in this version
- Route map can calculate from current location or use Tashkent as a fallback origin when location permission is not granted.
- Clearer approximate-vs-road-route messaging and a fallback estimate that is explicitly labelled approximate.
- Map reset and copy-route utilities.
- Passenger search validates visible route inputs first, sorts matching offers by price, and gives clearer empty states.
- Driver page includes a pre-publish checklist and clearer route/listing guidance.
- Keyboard escape support for modal/profile overlays, visible keyboard focus, and date minimums.
- Small-screen panel improvements and more consistent spacing.

## Important limitations
This is still a **front-end prototype**, not a deployed ride-sharing service:
- Authentication is not secure and does not verify phone numbers or emails.
- Driver listings are stored locally in the browser; they do not sync across devices.
- Seeded DEMO drivers and trips are fictional and must not be treated as real offers.
- Maps, geocoding and routing rely on public OpenStreetMap/Nominatim/OSRM services; availability and accuracy are not guaranteed.
- Card payment is a visual demo only. Never enter real card details.
- A production service needs a secure backend/database, verified accounts and driver documents, privacy/security review, abuse reporting, booking notifications, and a compliant payment provider.
