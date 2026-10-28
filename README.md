# Expanwell — V1 concept

A premium property-discovery homepage concept for Expanwell Realty Advisory.

## Included in V1
- Responsive cinematic hero with headline and calls to action
- Curated property cards with search and price/type filters
- Property detail modal with verification checklist
- Select up to three properties for side-by-side comparison
- Site-visit / virtual walkthrough request form
- Responsive mobile navigation and reduced-motion handling
- Clear notices that sample listing details are illustrative and not verified

## Run locally
This is a dependency-free static site. Open `index.html` in a browser or serve the repository root with any static web server.

## Hero video
The homepage expects the approved 10-second video at `/hero.mp4`. The file is not yet in this repository, so the hero uses a cinematic poster image as a fallback until the video asset is added. Add the approved video as `hero.mp4` in the repository root to enable autoplay, muted looping playback. Keep the source clip rights-cleared and optimized for web delivery.

## Important demo limitations
- Property names, prices, configurations and features are illustrative placeholders and must be verified before public use.
- The booking form stores demo requests in the current browser session only; it does not notify an agent, check a calendar, or confirm appointments.
- No live property inventory, maps/commute API, CRM, authentication or investment data feed is connected yet.

## Version plan
- **V1:** Homepage, discovery filters, property detail modal, compare flow, demo visit request.
- **V2:** Replace placeholder data with verified listing data; improve property detail pages and add location/commute intelligence.
- **V3:** Connect booking requests to a secure backend/CRM and implement agent availability, confirmation, rescheduling and follow-up.
- **V4:** Add transparent investment scenarios with source dates, assumptions and sensitivity analysis.
