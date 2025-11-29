# L'IA en Recherche : Objet d'étude et outil méthodologique

Présentation Quarto sur l'intelligence artificielle dans le contexte de la recherche.

## Structure du projet

```
.
├── index.qmd              # Fichier principal de la présentation
├── _quarto.yml           # Configuration Quarto
├── assets/               # Ressources (images, CSS, etc.)
│   ├── images/          # Images de la présentation
│   └── custom.css       # Styles CSS personnalisés
├── .nojekyll            # Nécessaire pour GitHub Pages
└── README.md            # Ce fichier
```

## Développement local

Pour prévisualiser la présentation en local :

```bash
quarto preview index.qmd
```

Pour générer la présentation :

```bash
quarto render index.qmd
```

## Déploiement sur GitHub Pages

1. Assurez-vous que GitHub Pages est configuré pour servir depuis la branche `main` et le dossier racine (ou `/docs` selon votre configuration)
2. Après avoir rendu la présentation, commitez les fichiers générés
3. La présentation sera accessible à l'URL de votre GitHub Pages

Ou utilisez GitHub Actions pour automatiser le déploiement :

```bash
quarto publish gh-pages
```

## Technologies

- [Quarto](https://quarto.org/)
- [Reveal.js](https://revealjs.com/) pour les slides interactives
