Rekenen Oefenen Pro v1.0
==========================

Bestanden
- tafels-oefenen-pro.html
- style.css
- app.js
- manifest.json
- sw.js
- icon-192.png
- icon-512.png
- ok.wav (bestaand geluidsbestand zelf toevoegen)
- no.wav (bestaand geluidsbestand zelf toevoegen)

Belangrijk
De HTML-bestandsnaam is bewust behouden, zodat de bestaande GitHub Pages-link en PWA-start-URL blijven werken.
De app migreert de oude naam, geselecteerde tafels en lastige tafelsommen automatisch naar het eerste profiel.

Testen
1. Plaats ook de bestaande ok.wav en no.wav in dezelfde map.
2. Start lokaal met: python -m http.server 8080
3. Open: http://localhost:8080/tafels-oefenen-pro.html
4. Test eerst in een gewoon browsertabblad.
5. Publiceer daarna de bestanden op GitHub Pages.

Bij een oude PWA-versie
De cache heet nu rekenen-oefenen-pro-v1. Na publicatie de pagina eenmaal vernieuwen. Als de geinstalleerde PWA oud blijft, sluit de app volledig en open opnieuw. Alleen indien nodig de PWA opnieuw installeren.
