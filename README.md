# CAMP MARL – Shop-Vorschau

Temporäre, öffentlich erreichbare Vorschau des CAMP-MARL-Onlineshops (WordPress + WooCommerce).
Die Seite läuft mit **WordPress Playground** vollständig im Browser der Besucherin bzw. des Besuchers –
ohne Server und ohne Verbindung zur Live-Website.

**▶ Vorschau öffnen:**
https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/fztw5dxr6x-design/camp-marl-preview/main/blueprint.json

- Der erste Start dauert je nach Verbindung etwa 30–90 Sekunden (WordPress und WooCommerce werden im Browser eingerichtet).
- Jede Person erhält eine eigene, isolierte Kopie. Testbestellungen und Anfragen bleiben im eigenen Browser
  und verschwinden beim Neuladen der Vorschau.
- Es werden keine E-Mails versendet und keine Zahlungen ausgeführt (Zahlart: Vorkasse, Testmodus).
- Backend: `/wp-admin` – Benutzer `admin`, Passwort `password` (nur innerhalb der eigenen Browser-Kopie).
- Produkte mit `[TEST]` sind Testartikel. „Dometic Residence AIR“ zeigt die Originalfotos, Preis und Beschreibung folgen.
- Suchmaschinen werden ausgeschlossen (`noindex`).

Inhalt dieses Repositorys (automatisch erzeugt, nicht von Hand bearbeiten):

| Datei | Zweck |
|---|---|
| `blueprint.json` | Anleitung für WordPress Playground: WordPress 7.1, WooCommerce 11.3.1, Deutsch, Theme, Plugin, Testdaten |
| `camp-marl-preview.zip` | Theme `camp-marl`, Plugin `camp-marl-core`, Vorschau-Hinweis, Einrichtungsskripte, Testdaten |

Quelle: privates Projekt-Repository, Build mit `bash preview/build.sh`.
