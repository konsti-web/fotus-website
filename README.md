# Fotus — Website

Premium-Coaching-Software Landingpage. Single-Scroll, voll responsiv, mit cineastischem Fitness-Video im Hero.

Implementiert aus dem Claude-Design-Handoff "Fotus Website.html".

## Lokal ansehen

Einfach `index.html` im Browser öffnen — oder einen kleinen Server starten:

```bash
python3 -m http.server 8000
# dann http://localhost:8000 öffnen
```

## Live (GitHub Pages)

Die Seite wird über GitHub Pages aus dem `main`-Branch ausgeliefert.

## Dateien

- `index.html` — die komplette Seite
- `fotus-web.css` — Styles (Lenus-inspiriertes Premium-Design, ein Mint-Akzent)
- `image-slot.js` — Platzhalter-Komponente für das Gründerfoto
- `.nojekyll` — sorgt dafür, dass GitHub Pages alle Dateien unverändert ausliefert

## Anpassen

- **Hero-Video:** Quelle in `index.html` im `<video>`-Tag (`assets.mixkit.co/...`) gegen eigenes Material tauschen.
- **Gründerfoto:** im Abschnitt „Die Gründer" das `image-slot` — auf der statischen Seite zeigt es den Platzhalter; eigenes Foto als `src` eintragen.
- **Kontakt:** `hello@fotus-fitness.de` an den `mailto:`-Links anpassen.
