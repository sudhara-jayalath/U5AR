# U5 Arenen Pflanzplaner

Interaktiver Pflanzplaner für die U5-Haltestelle Arenen (Hamburg), Projekt U5M2000-6000, Phase 3.
Er zeigt drei Bereiche: **Mini-Stadtwaldgarten**, **Vorplatz** und **Randbereich**.

*Interactive planting planner for the U5 Arenen station (Hamburg), project U5M2000-6000, Phase 3. It covers three areas: the mini urban forest garden, the station forecourt (Vorplatz) and the verge behind the guardrails (Randbereich). The interface is bilingual (DE / EN).*

## Öffnen

- **Online:** über GitHub Pages, siehe unten.
- **Lokal:** `index.html` herunterladen und im Browser öffnen. Eine Internetverbindung lädt nur die Schriften.

## Funktionen

- Flächen, Grundwasserstand (MHGW), Arten, Anteile, Dichten und Charakter je Bereich ändern.
- Maßstäbliche Schnitte, die sich live ändern: Sichtachse zum Stationsdach, Baumgruben und Grundwasser, Leitplanke und Baumzone.
- Ökologie-Kennwerte: heimische Arten, Bienenweide, Vogelnährgehölze, immergrüne Anteile, giftige Arten, Eignung für den Grundwasserstand.
- Massen je Bereich und gesamt, Export als CSV (für die BIM-Planung).
- Änderungen bleiben in Ihrem Browser gespeichert. **Teilen:** „Szenario als JSON“ exportieren und weitergeben; andere laden die Datei mit „JSON laden“.

## GitHub Pages aktivieren

1. Repository → **Settings** → **Pages**.
2. Unter *Build and deployment*: **Source = Deploy from a branch**.
3. **Branch = main**, Ordner **/ (root)** → **Save**.
4. Nach etwa einer Minute ist der Planer erreichbar unter: `https://sudhara-jayalath.github.io/U5AR/`

## Hinweise

- Alle Werte sind Startwerte für Phase 3 (Stand der Excel-Tabellen vom 22.10.2026). Beispielwerte sind im Planer markiert.
- Die Grundwasser-Grenzwerte im Planer sind Planungsheuristiken (Annahmen) und ersetzen kein Gutachten.
- Quellen: FLL Baumpflanzungen Teil 2:2010, GALK-Straßenbaumliste, Stadt Bern (Wurzelraum), RPS 2009, Landesforst MV (Pflanzverbände), BfN (LRT 9190), ErMiV (Ursprungsgebiete). Links stehen im Fuß des Planers.
- Das Repository ist öffentlich: Die Seite und ihre Inhalte sind für alle sichtbar.
