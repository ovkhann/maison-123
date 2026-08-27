# Maison 123 La Roche-sur-Yon — maquette de refonte

Site vitrine statique : un seul fichier `index.html` + un dossier `images/`.

## Mise en ligne (GitHub Pages)
1. Créer un dépôt **public** sur github.com
2. Déposer le contenu de ce dossier à la racine du dépôt
3. Settings → Pages → Source : « Deploy from a branch » → branche `main`, dossier `/ (root)`
4. Le site est en ligne sous `https://<compte>.github.io/<depot>/` (1 à 2 minutes)

## Modifier le site
Tout est dans `index.html` :
- objet `IMG` (haut du `<script>`) : chemins des images
- tableau `P` : les produits (nom, prix, tailles, description, composition, entretien)
- tableau `LOOKS` : les looks de la boutique

## À compléter
Adresse, horaires et téléphone de la boutique, et vérification des compositions
face aux étiquettes des produits.
