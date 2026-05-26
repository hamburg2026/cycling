# Rennrad Routenplaner

## Automatische Pull Requests

Nach jedem `git push` auf den Feature-Branch automatisch einen Pull Request gegen `main` erstellen, sofern noch kein offener PR für diesen Branch existiert.

## Projekt

Single-file React 18 App (`index.html`) ohne Build-Schritt — alle Änderungen gehen in diese eine Datei.

- Routing: OpenRouteService API (`cycling-road`-Profil, `round_trip` + Via-Route)
- Karte: Leaflet.js mit CartoDB Dark Tiles
- Geocoding: Nominatim (OpenStreetMap)
- Höhenprofil: reines SVG (keine externen Chart-Bibliotheken)
- GPX-Export: clientseitig als Blob-Download

## Branch

Feature-Entwicklung auf `claude/cycling-route-planner-6jgdz`, Merge-Ziel ist `main`.
