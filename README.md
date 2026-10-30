# ePortfolio – Grégoire Descheemaeker

Site statique : aucun template ni installation nécessaire.

```
index.html
assets/img/  hero.jpg · portrait.jpg · profil.jpg
```

## Publier sur GitHub Pages
1. Crée un dépôt public (par ex. `ton-pseudo.github.io`).
2. Envoie `index.html` et le dossier `assets` **à la racine** du dépôt.
3. Settings > Pages > Deploy from a branch > `main` / `(root)` > Save.
4. Le site est en ligne après 1 à 2 minutes.

## Modifier le contenu
- Textes français : directement dans `index.html`.
- Textes anglais : dans l'objet `EN` du `<script>` en bas du fichier (même clé que l'attribut `data-i18n` du texte français).
- Pour partager directement la version anglaise : `https://ton-site/?lang=en`.
