# GlückskeksNinja – Relaunch

Website-Relaunch mit modernem Tech-Stack, SEO- und GEO-Optimierung.

## Technologie

- **Astro 5** – Statisches Site-Framework, schnell, SEO-freundlich
- **Tailwind CSS 4** – Utility-First-Styling
- **TypeScript** – Typsicherheit

### Warum Astro?

- Zero JavaScript by default (schnelle Ladezeiten, gute Core Web Vitals)
- Built-in SEO: Meta-Tags, kanonische URLs
- Dateibasiertes Routing
- Einfache Integration von Schema.org/JSON-LD

## Projektstruktur

```
src/
├── components/     # Header, Footer
├── data/           # Site-Daten, Entity-Definition (GEO)
├── layouts/        # Layout mit SEO-Meta
├── pages/          # Alle Seiten
├── styles/         # Globales CSS, Tailwind, Corporate Design
```

## SEO & GEO

- **Eine H1 pro Seite** – korrekte Hierarchie (H1 → H2 → H3)
- **Canonical URLs** – keine Duplicate-Content-Probleme
- **Schema.org** – Organization, WebSite, FAQPage, Article, Course, ContactPage
- **Entity-Klarheit** – zentrale Definition in `src/data/site.ts`
- **robots.txt** & **Sitemap** – automatisch generiert

## Entwicklung

```bash
npm run dev      # Dev-Server (localhost:4321)
npm run build    # Produktions-Build
npm run preview  # Vorschau des Builds
```

## Nächste Schritte

- [ ] Rechtliche Seiten (Impressum, Datenschutz) mit echten Angaben
- [ ] Cookie-Banner (DSGVO) integrieren
- [ ] Selbstliebe-Kurs: Anmeldungsformular
- [ ] Sprüche/Affirmationen aus CMS/API laden
- [ ] OG-Image für Social Sharing
