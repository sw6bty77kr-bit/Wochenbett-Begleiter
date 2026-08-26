Wochenbett Begleiter – PWA

Dateien:
- index.html
- manifest.webmanifest
- service-worker.js
- icon-192.png
- icon-512.png

Installation:
1. Den gesamten Ordner auf einen HTTPS-fähigen statischen Webhost laden, z. B. GitHub Pages oder Cloudflare Pages.
2. Die veröffentlichte URL einmal in Safari auf dem iPhone öffnen.
3. Teilen → Zum Home-Bildschirm.
4. Danach startet die App im Standalone-Modus und funktioniert nach dem ersten Laden auch offline.

Wichtig:
Eine PWA kann nicht zuverlässig direkt aus der Dateien-App oder über file:// installiert werden. Service Worker benötigen HTTPS oder localhost.
