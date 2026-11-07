# Legal Pages — Stefan Marx

Statische rechtliche Informationsseiten für Giggle Punk und GigglingHome.

## Deployment auf GitHub Pages

1. Den Inhalt dieses Ordners in ein GitHub-Repository hochladen (das öffentliche Repo enthält die postalische Adresse im HTML und in der Git-Historie).
2. Unter **Settings → Pages** „Deploy from a branch“, Branch `main`, Verzeichnis `/ (root)` auswählen.
3. Custom Domain: `impressum.stefanmarx.de` (in `CNAME` enthalten).
4. Beim Domain-Provider den `CNAME`-Record `impressum` auf `<GITHUB-USERNAME>.github.io` setzen (GitHub-Benutzernamen einsetzen).
5. Nach DNS-Verfügbarkeit in Pages „Enforce HTTPS“ aktivieren.
6. URLs prüfen: `/`, `/datenschutz/`, `/giggle-punk/`, `/gigglinghome/`.

## Lokal testen

```bash
python3 -m http.server 8000
```

Danach `http://localhost:8000/` öffnen.

## Vor Veröffentlichung prüfen

- Anschrift ist **Friedrichsberger Str. 5, 10243 Berlin**. Vollständigkeit und Schreibweise selbst kontrollieren.
- Umsatzsteuer-ID / Wirtschafts-ID falls vorhanden und offenlegungspflichtig ergänzen.
- Prüfen, ob ein weiterer Weg zur schnellen unmittelbaren Kommunikation erforderlich ist.
- Datenschutztext anhand des konkreten Hosting-Setups und späterer Anpassungen fachlich prüfen.
- Instagram/Pinterest-Profile eindeutig und direkt zum Impressum verlinken.

Dies ist ein technischer Entwurf, keine anwaltliche Prüfung.
