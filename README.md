# kookboek-site

Statische webapp van het persoonlijke Kookboek, gepubliceerd via GitHub Pages.

- `index.html` — de volledige app (één bestand).
- `vendor/supabase.js` — Supabase JS-client (lokaal meegeleverd, geen CDN-afhankelijkheid).

De data staat **niet** in deze repo maar in Supabase (Postgres), achter login en Row Level Security.
De publieke "publishable key" in `index.html` is bedoeld om openbaar te zijn: zonder ingelogde gebruiker met een rol geeft de database niets terug.

Lokaal draaien: `python -m http.server 8000` en open http://localhost:8000.
