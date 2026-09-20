# CUIOM Staff Attendance & Report — Current Working Project

This package contains the current working CUIOM Staff + Admin system as of 19 September 2026.

## Included
- `public/index.html` — Admin portal, including Staff management, attendance, reports and activity reports.
- `public/staff-login.html` — Staff login portal with Clock In/Out and Daily Activities Report.
- `public/logo.png` — CUIOM branding logo.
- `public/manifest.json` — PWA manifest.
- `public/sw.js` — Service worker.
- `server/server.js` — Render/Express backend with cloud persistence and Staff/Admin authentication.
- `package.json` — Node dependencies/start script.
- `render.yaml` — Render deployment configuration.

## Important
Keep the project structure unchanged when uploading/deploying. Do not place the frontend files inside the server folder.

Set the required Render environment variables used by `server/server.js` (including `JWT_SECRET`, `ADMIN_USER`, `ADMIN_PASS`, and `DATABASE_URL`). Do not store real passwords in this README or in the source files.


## CUIOM branding note
This copy has been separated and renamed for CHRIST UNIVERSAL IMPACT OUTREACH MINISTRIES (CUIOM).
Replace `public/logo.png` with the official CUIOM logo before deployment if the logo is not already present.
Keep the filename `logo.png` so all existing Staff/Admin screens continue to reference it.


## CUIOM branding
Organization: CHRIST UNIVERSAL IMPACT OUTREACH MINISTRIES (CUIOM).
The official CUIOM logo supplied by the user is installed as the project's logo.png asset.
This project is intended to remain separate from ANREM and GIGM data and deployment resources.
