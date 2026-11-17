HALF MARATHON 2027 – iPhone Web-App

INHALT
- index.html: vollständige App
- manifest.webmanifest: Installationsmetadaten
- sw.js: Offline-Caching
- icon-192.png / icon-512.png: App-Symbole

WICHTIG ZUR INSTALLATION
Eine iPhone-Web-App mit Home-Bildschirm- und Offline-Unterstützung muss über HTTPS bereitgestellt werden. Das ZIP allein ist noch keine installierte App und kann nicht direkt aus der Dateien-App als PWA installiert werden.

1. Lade den kompletten Ordner auf einen statischen HTTPS-Webhost (z. B. GitHub Pages oder Netlify).
2. Öffne die veröffentlichte HTTPS-Adresse in Safari auf dem iPhone.
3. Tippe auf Teilen → Zum Home-Bildschirm → Hinzufügen.
4. Öffne die App über das neue Symbol.

DATENSPEICHERUNG
Trainingsdaten werden lokal im Browser (localStorage) gespeichert. Sie werden nicht automatisch zwischen Geräten synchronisiert. Nutze im Tab „Laufprotokoll“ regelmäßig „Daten exportieren“, um ein Backup zu sichern.

HINWEIS
Der Wettkampftag ist als 14. März 2027 voreingestellt. Du kannst ihn direkt in der App unter „Wettkampftag festlegen“ ändern.
