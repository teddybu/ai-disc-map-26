# AI Discourse Map 2026

Interaktive Karte zum AI-Diskurs 2026. Personen und Positionen werden anhand von zwei Achsen (x/y) in Gruppen dargestellt.

## Inhalt

- `index.html` – Single-Page-Anwendung (HTML, CSS und JavaScript in einer Datei) mit Steuerungspanel und Karte
- `data.csv` – Datengrundlage

## Datenformat (`data.csv`)

| Spalte   | Beschreibung                          |
|----------|---------------------------------------|
| `name`   | Name der Person bzw. Position         |
| `meta`   | Meta-Kategorie (z. B. Pro)            |
| `legend` | Legendeneintrag (z. B. AGI)           |
| `x`, `y` | Koordinaten auf der Karte (-1 bis 1)  |
| `group`  | Gruppe (z. B. AGI Transformation)     |
| `url`    | Quelle / weiterführender Link         |

## Nutzung

`index.html` im Browser öffnen. Bei lokalem Zugriff auf die CSV ggf. einen lokalen Server starten:

```sh
python3 -m http.server 8000
```

Danach `http://localhost:8000` aufrufen.
