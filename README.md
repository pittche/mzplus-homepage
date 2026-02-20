# MZplus – 100 Jahre Medienkompetenz

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/pittche/mzplus-homepage)

Homepage des **MZplus Saarpfalz-Kreis** zum 100-jährigen Jubiläum (1926–2026).

## Features

- 🎬 Film-Countdown-Intro
- 📽 6 Tabs: Start, Geschichte, Leistungen, MakerSpace, Vision, Kontakt
- 🕰 Interaktiver Zeitstrahl 1926–2026 mit Originalbildern
- 🎞 Animierter Film-Strip-Scroller
- 📱 Vollständig mobil-responsiv
- 💻 Terminal-Easter-Egg auf der Kontaktseite

## Schnellstart: Netlify Deployment

### Option 1: Klick-Deploy (einfachste Methode)
1. Klicke auf den "Deploy to Netlify" Button oben
2. Netlify-Account anmelden / einloggen
3. Repository verbinden → Done ✅

### Option 2: Manuell via Netlify CLI
```bash
npm install -g netlify-cli
netlify login
netlify init
netlify deploy --prod
```

### Option 3: GitHub Actions (automatisch)
1. Netlify-Site erstellen: [app.netlify.com](https://app.netlify.com) → "New site" → "Import from GitHub"
2. Repository auswählen: `pittche/mzplus-homepage`
3. Build-Einstellungen: keine (statische Site)
4. Deploy! Netlify erkennt `netlify.toml` automatisch.
5. Für GitHub Actions: `NETLIFY_AUTH_TOKEN` und `NETLIFY_SITE_ID` als Repository Secrets hinterlegen.

## Technologie

- Reines HTML/CSS/JavaScript (kein Framework nötig)
- Google Fonts: Cormorant Garamond, DM Mono, Crimson Pro
- Netlify für Hosting

## GitHub Repository

[https://github.com/pittche/mzplus-homepage](https://github.com/pittche/mzplus-homepage)

---

*MZplus Saarpfalz-Kreis · 1926–2026 · „Gestern Filmrolle. Heute Cloud."*
