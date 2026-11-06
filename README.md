# Site vitrine de l'équipe de développeurs

Site 100 % front-end (HTML / CSS / JavaScript) pour présenter chaque développeur de l'équipe.

## Structure

```
index.html          → page d'accueil : galerie des développeurs
style.css           → styles communs
modele-profil.html  → modèle de page personnelle (à copier)
profil-<prenom>.html → la page de chaque membre
images/             → les photos (images/<prenom>.jpg)
```

## Comment ajouter ma page (4 étapes)

1. **Copier** `modele-profil.html` et le renommer `profil-<prenom>.html` (ex. `profil-marie.html`).
2. **Remplir** ma page : nom, présentation, compétences, projets, liens.
3. **Ajouter ma photo** dans `images/` (carrée de préférence, ex. `images/marie.jpg`).
4. **M'ajouter à la galerie** : dans `index.html`, copier un bloc `<a class="dev-card">…</a>`, puis changer le lien, la photo, le nom et le rôle.

## Règles pour travailler ensemble

- Ne modifier **que** sa propre page et sa propre carte dans `index.html`.
- Pour `style.css`, se mettre d'accord avant de changer quelque chose de commun. Pour un style perso, utiliser une balise `<style>` dans sa page.
- Travailler sur sa propre branche Git (`git checkout -b profil-prenom`) puis proposer une Pull Request.

## Entraide

Des sessions de partage sont organisées : ceux qui maîtrisent le plus aident les autres sur le design, l'intégration et le JavaScript.

## Idées pour la suite

- Barre de recherche / filtre par compétence sur la galerie
- Mode clair / sombre
- Données des profils dans un fichier `devs.json` pour générer la galerie en JavaScript
- Animations et page de contact
- Mise en ligne gratuite avec GitHub Pages
