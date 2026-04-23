Cornets Tinctoris — Site one-page
==================================

Structure du projet
-------------------
cornets-tinctoris/
├── index.html            → ouvrir ce fichier dans un navigateur
├── assets/
│   ├── logo.png          → logo TCC/BT sur fond noir
│   ├── benoit.jpg        → photo de Benoît en concert (cornet à bouquin)
│   └── stand.jpg         → photo du stand avec les instruments alignés
└── README.txt

Étape à faire avant mise en ligne
---------------------------------
Les trois images fournies doivent être déposées dans le dossier `assets/`
avec EXACTEMENT ces noms :

  assets/logo.png
  assets/benoit.jpg
  assets/stand.jpg

Le site fonctionne même sans ces images (un fallback typographique s'affiche),
mais il est conçu pour que ces trois visuels soient en place.

Technologies
------------
• HTML5 pur
• Tailwind CSS via CDN (aucune installation nécessaire)
• Polices Google Fonts : Cormorant Garamond + Outfit
• Aucun build, aucun framework — il suffit de double-cliquer index.html

Personnalisation rapide
-----------------------
• Email       → recherche "b.tainturier@gmail.com" dans index.html
• Téléphone   → recherche "06 61 73 20 84" (et "+33661732084" pour le tel:)
• Couleur     → variables CSS en haut du <style> : --ink, --ivory, --copper
• Typographie → balise <link> Google Fonts + tailwind.config.fontFamily

Mise en ligne
-------------
N'importe quel hébergeur statique convient : Netlify, Vercel, Infomaniak,
OVH, GitHub Pages, Cloudflare Pages — il suffit de déposer le dossier.
