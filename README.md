# Landingpage Andreas Schulz (v4)

Statische Seite ohne Build-Schritt. Inhalt dieses Ordners 1:1 als Repo-Root verwenden.

- index.html: komplette Seite inkl. Impressum und Datenschutz
- img/: Fotos
- fonts/: lokal eingebundene Schriften (Hanken Grotesk, SIL Open Font License)
- netlify.toml: Netlify-Konfiguration (kein Build, Publish-Verzeichnis = Root)

Deployment: Neues Netlify-Projekt aus diesem GitHub-Repo anlegen, Build command leer lassen, Publish directory ".". Danach unter Domain management die eigene Domain verbinden; HTTPS stellt Netlify automatisch bereit.
