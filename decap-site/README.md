# Petits Trésors — site + administration Decap CMS

## Structure du projet

- `index.html` — le site de la boutique.
- `content/products.json` — la liste des articles (c'est ce fichier que l'administration modifie).
- `images/products/` — les photos des articles déjà en ligne.
- `images/uploads/` — dossier où sont rangées les nouvelles photos ajoutées depuis l'administration.
- `images/logo.jpg` — le logo de la boutique.
- `admin/` — l'interface d'administration (Decap CMS). Accessible depuis `votre-site.netlify.app/admin/`.
- `netlify.toml` — réglages de publication pour Netlify.

## Pour publier une modification manuellement

Toute modification faite depuis `/admin/` est enregistrée automatiquement dans ce dépôt Git et republiée par Netlify en 1 à 2 minutes — vous n'avez rien d'autre à faire.

Voir le guide complet fourni séparément pour la mise en place initiale (compte GitHub, connexion à Netlify, activation de l'authentification).
