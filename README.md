# Reclamații Andreea

GitHub Pages: index.html, style.css, app.js.
Cloudflare Worker: worker.js, wrangler.toml.

1. Creează un secret Gist cu comments.json = [].
2. Creează un token GitHub cu Gist read/write.
3. Creează un Cloudflare Worker, adaugă worker.js și wrangler.toml.
4. Adaugă Worker secrets: GITHUB_TOKEN și GIST_ID.
5. Publică Workerul și copiază URL-ul.
6. Pune URL-ul în app.js la API_BASE_URL.
7. Încarcă index.html, style.css și app.js în GitHub Pages.

Nu pune tokenul în app.js. Parola interfeței admin este admin$123#.
