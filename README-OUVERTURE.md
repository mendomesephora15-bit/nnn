# BON GOUT — Pages accessibles (HTML/CSS conservés)

## Important : ne pas fusionner les pages dans un seul fichier HTML
Les codes sont regroupés dans les deux fichiers texte pour faciliter la copie, mais le navigateur a besoin de quatre fichiers HTML séparés.

## Structure à conserver dans VS Code
```text
BON-GOUT-PAGES-ACCESSIBLES/
├── index.html
├── menu.html
├── contact.html
├── admin.html
├── css/
│   ├── style.css
│   └── admin.css
├── images/
├── TOUS-LES-CODES-HTML.txt
└── TOUS-LES-CODES-CSS.txt
```

## Pour ouvrir les pages correctement
1. Décompressez le dossier ZIP.
2. Dans VS Code, choisissez **File > Open Folder** et ouvrez le dossier `BON-GOUT-PAGES-ACCESSIBLES`.
3. Vérifiez que `index.html`, `menu.html` et `contact.html` sont côte à côte, et que le dossier `css` est au même niveau.
4. Faites un clic droit sur `index.html`, puis **Open with Live Server**.
5. Dans le site ouvert, cliquez sur **Menu & Ordering** ou **Contact & Reservations** dans la barre de navigation.

Vous pouvez aussi ouvrir directement `menu.html` ou `contact.html` avec Live Server.

## Si les liens ne fonctionnent toujours pas
- Ne mettez pas les pages dans des sous-dossiers différents.
- Ne renommez pas `menu.html` en `Menu.html`, `menus.html` ou autre : le nom doit correspondre exactement au lien.
- Ne copiez pas les quatre pages l'une à la suite de l'autre dans un seul `index.html`.
- Assurez-vous d'avoir extrait le ZIP avant de lancer Live Server.

## Codes regroupés
- `TOUS-LES-CODES-HTML.txt` contient les quatre pages, séparées par des titres indiquant le nom de chaque fichier.
- `TOUS-LES-CODES-CSS.txt` contient les deux feuilles de style, séparées de la même manière.

**Note :** le HTML et le CSS ont été conservés tels quels. Les fonctions de commande, panier, formulaires, authentification et gestion Supabase nécessitent encore l'intégration JavaScript/Supabase prévue dans le projet.
