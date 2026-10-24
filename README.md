# FitForge — Fitness Tracker

Log exercise sessions, minutes, and rough calorie estimates.

## Features
- Responsive mobile-friendly interface
- Add and delete records
- Dashboard statistics
- Persistent localStorage data
- No dependencies, login, API key, or backend

## Run locally
Open `index.html` in a modern browser. For best compatibility, use VS Code Live Server or `python -m http.server 8000` and visit http://localhost:8000.

## Deploy on GitHub Pages
1. Create a public GitHub repository named `fitforge-tracker`.
2. Upload `index.html`, `style.css`, `app.js`, and `README.md` to the repository root.
3. Open **Settings → Pages**, select **Deploy from a branch**, choose **main** and **/(root)**, then save.
4. After deployment, your site should be at `https://YOUR-USERNAME.github.io/fitforge-tracker/`.

## Data privacy
Entries stay only in the browser's localStorage and can disappear if site data is cleared. They do not sync across devices.

Calories are rough activity-based estimates (3/6/9 kcal per minute), not individualized medical measurements.

## License
MIT
