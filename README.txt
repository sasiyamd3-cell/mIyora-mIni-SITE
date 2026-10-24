MIYORA MD MINI BOT - Vercel Frontend

Included:
- index.html (copied from main.html so the site opens at the domain root)
- main.html
- pair.html
- react.html
- settings.html
- admin.html
- vercel.json (proxies /code API routes to the existing Heroku app)

Deploy:
1. Extract this ZIP.
2. Upload the folder to a GitHub repository (keep vercel.json and HTML files in the repository root).
3. In Vercel, Add New -> Project -> import that repository.
4. Framework Preset: Other. Build Command: leave empty. Output Directory: leave default/root (or set `.` if required by the UI).
5. Deploy.
6. Test the Vercel site, then open /pair.html and try pairing.

Important:
- Backend/API requests under /code are proxied to https://fndenda-354d74328f43.herokuapp.com.
- This only works if that Heroku app continues to serve the /code and /code/api/* routes. Keep the bot backend running on Heroku.
- If Vercel reports a rewrite/config error, share the exact deployment log.
