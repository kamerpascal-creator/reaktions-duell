# Changelog

Alle nennenswerten Änderungen an diesem Projekt werden hier festgehalten.

Das Format orientiert sich an [Keep a Changelog](https://keepachangelog.com/de/1.1.0/),
und das Projekt folgt [Semantic Versioning](https://semver.org/lang/de/).

## [Unveröffentlicht]

## [1.0.0] – 2026-09-09

### Hinzugefügt

- Solo-Modus mit Reaktionszeit-Messung und Bestenliste der letzten 10 Versuche
  (lokal im Browser via `localStorage` gespeichert)
- Duell-Modus für zwei Spieler an einer Tastatur (Tasten `A` / `L`) oder per Touch
- Fehlstart-Erkennung; im Duell geht der Punkt an den Gegner
- Statistik-Leiste: Letzte / Best / Ø der letzten 10
- Dunkles, mobilfreundliches UI in einer einzigen `index.html` ohne Build und ohne Abhängigkeiten
- MIT-Lizenz
- README mit Anleitung zum Starten und Spielen, Screenshot und Badges
- Favicon (Blitz-SVG) sowie `description`-, Open-Graph- und Twitter-Card-Meta-Tags
- Dediziertes 1200×630-Vorschaubild für Social-Media-Links (`docs/og-image.png`)
- Fußzeilen-Link zum GitHub-Repo im Spiel
- Online-Version über GitHub Pages: <https://kamerpascal-creator.github.io/reaktions-duell/>

### Behoben

- Rechte Spielhälfte im Duell zeigte „Spieler L" statt „Spieler B"
- Uneinheitlicher Starthinweis auf der rechten Spielhälfte

[Unveröffentlicht]: https://github.com/kamerpascal-creator/reaktions-duell/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/kamerpascal-creator/reaktions-duell/releases/tag/v1.0.0
