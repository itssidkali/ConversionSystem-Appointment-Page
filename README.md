# ConversionSystem™ Appointment Booking Page — GitHub/Vercel package

This folder is ready to upload to the **root of a new GitHub repository** and import as a **separate Vercel project**.

## Files
- `index.html` — assembled appointment-booking landing page, using the supplied sections in the supplied order.
- `thank-you/index.html` — supplied standalone appointment thank-you page, retained as received.
- `vercel.json` — routes `/thank-you` to `thank-you/index.html`.
- `sections/` — copies of the 10 separately uploaded GHL section snippets, retained verbatim.
- `booking-support/` — copies of the four snippets pasted in chat: form popup, sticky CTA, free strategy session section, and website/sales-system section.
- `SHA256SUMS.txt` — hashes for the source copies and deploy files, for checking file integrity.

## Deploy
1. Extract this ZIP locally.
2. Create a new private GitHub repository (do not reuse/overwrite the onboarding-fitness or 30-day-challenge repo).
3. Upload the **contents** of this folder at repository root, so `index.html`, `vercel.json`, `sections/`, `booking-support/`, and `thank-you/` are at the top level.
4. In Vercel, create a **new project** and import this new repository.
5. Framework Preset: `Other`; use static deployment (no build command; output directory `.`).
6. Deploy and test `/`, `/thank-you`, and `/thank-you/`.

## Booking form
The popup/form URL is the supplied LeadConnector URL:
`https://api.leadconnectorhq.com/widget/form/349k6XqxJsWlr88axN4V`

The form links are retained. External iframe loading and appointment submission depend on LeadConnector availability/configuration. The uploaded source code itself is not a guarantee of a successful real booking; test an appointment after deploying.

## Important
The project includes the supplied original snippets. Page assembly only wraps them in a normal HTML document and places them into the requested order. No payment code is used on this booking page. Keep this repository private if you want the source code private.
