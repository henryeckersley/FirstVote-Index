# FirstVote Index

Ready-to-deploy civic-tech microproject for auditing how easy local election systems are for first-time voters to navigate.

## What is included
- `index.html` – landing page + audit form + public report cards
- `styles.css` – styling
- `app.js` – scoring, storage, export tools
- `server.js` – tiny Node backend for local hosting / simple API
- `launch-email.txt` – outreach copy
- `deployment-notes.md` – how to publish fast
- `sample-outreach-tracker.csv` – simple contact tracker
- `.gitignore`

## Run locally
```bash
node server.js
```
Then open `http://localhost:3000`.

## Notes
- Frontend works without the backend via `localStorage`.
- For a public launch, replace the demo entry with real audits.
