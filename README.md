# Shetach Batuach — שטח בטוח

Public information, support, legal and store-compliance pages for **שטח בטוח**.

[Open the app](https://shetachbatuach.com) · [Privacy](privacy.html) · [Support](support.html) · [Terms](terms.html) · [Delete account](account-deletion.html) · [Security](security.html)

שטח בטוח provides regional weather and point forecasts, rider hazard reports with optional photo and precise location, official updates, favorite areas, push and local reminders, riding mode, route history and quick in-ride hazard marking on supported mobile builds. Riding mode can continue route tracking in the background or while the screen is locked when the user explicitly starts a ride and grants the required operating-system permissions. Registered users can manage their profile, reports, favorites, notifications and account. Authorized administrators use a protected dashboard for moderation, notices and push messaging.

Production runs at **https://shetachbatuach.com** on Cloudflare. Android and iOS wrappers use the same production application.

## Public URLs

- App: https://shetachbatuach.com
- Privacy: `privacy.html`
- Support: `support.html`
- Terms: `terms.html`
- Account deletion: `account-deletion.html`
- Security reporting: `security.html`

The account deletion page is intended to serve as the external account/data deletion web resource required for app-store compliance. Users can also delete their account directly inside the app from **הפרופיל שלי → מחיקת חשבון**.

Support requests can be sent directly inside the app from **תפריט → צור קשר**; no external mail client is required. For signed-in users, the account email can be filled automatically in the support form.

Application source, production configuration, credentials and signing material remain private in `Shetach-Batuach-App`. This public repository contains only public website, support, legal and store-compliance material. Do not commit private keys, signing keystores, service-account credentials, API tokens, environment secrets or production database exports here.
