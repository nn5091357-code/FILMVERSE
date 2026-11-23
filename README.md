# FILMVERSE — Where Stories Become Cinema

A responsive, frontend-focused film production and management platform built with HTML5, CSS3 and vanilla JavaScript.

## Run locally
1. Extract the `FILMVERSE` folder.
2. Open the folder in VS Code.
3. Install/enable the **Live Server** extension.
4. Right-click `index.html` → **Open with Live Server**.

No build step or backend is required. Internet access is used for Google Fonts, Chart.js, profile placeholders and cinematic photography.

## Included pages
- Landing page, About, Contact
- Productions catalogue and individual project details
- Cast & crew directory
- Script library
- Shooting calendar
- Budget dashboard with Chart.js visualisations
- Equipment inventory and location catalogue
- Post-production milestone tracker
- Admin dashboard, project management and settings

## Demo data and persistence
The first visit loads 10 film projects, 16 cast/crew profiles, 8 equipment records, 6 locations, 4 scripts, sample expenses and shooting calls. Records are stored in browser `localStorage` under the `fv_` prefix. Use **Admin → Settings → Restore demo data** to reset the workspace, or Export data to download the current records.

## Important demo limitations
- This is a college-project frontend demo. There is no server-side authentication, multi-user sync, payment processing or database.
- Uploaded screenplay files are selected locally for preview/name display; file bytes are not persisted. A production deployment should use a backend file service.
- Contact form submissions are acknowledged in the browser and are not emailed.
- Replace sample people, contact details, project budgets and image URLs with verified information before public deployment.

## Technology
HTML5 · CSS3 · Vanilla JavaScript · Chart.js · localStorage · Unsplash image URLs · Google Fonts
