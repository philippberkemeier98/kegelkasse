# Kegelkasse – Web-App installieren

Die App ist eine einzelne Webseite, die offline funktioniert. Kostenlos, kein Apple-Konto nötig.

## 1. Online stellen (einmalig, ca. 10 Minuten)

**GitHub Pages (kostenlos, empfohlen)**
1. Kostenloses Konto auf github.com anlegen.
2. Neues Repository anlegen, z. B. `kegelkasse` (Public).
3. „Add file → Upload files“ und **alle Dateien aus diesem Ordner** hochladen (index.html, sw.js, manifest.webmanifest, die drei PNG-Icons).
4. Settings → Pages → Branch `main`, Ordner `/ (root)` → Save.
5. Nach 1–2 Minuten läuft die App unter `https://<dein-name>.github.io/kegelkasse/`.

Alternativ geht jeder andere Hoster, der HTTPS bietet (z. B. Cloudflare Pages, Netlify).

## 2. Aufs iPhone holen

1. Link in **Safari** öffnen.
2. Teilen-Symbol → „Zum Home-Bildschirm“.
3. App vom Home-Bildschirm starten. Ab jetzt läuft sie auch ohne Netz auf der Kegelbahn.

## 3. Daten sichern

Die Daten liegen nur auf diesem iPhone, in der Home-Bildschirm-App.
- Nach jedem Abend: Tab „Abende“ → Datenbank-Symbol oben rechts → **Backup sichern** → in iCloud Drive ablegen.
- Neues Handy: App installieren → **Backup laden**.
- Nicht die App vom Home-Bildschirm löschen, ohne vorher ein Backup zu sichern.

## Updates

Neue Version von index.html hochladen. Die App lädt sie beim nächsten Start mit Netz automatisch.
