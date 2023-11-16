---
title: "Introduction à Hugo et GitHub Pages"
date: 2023-11-16
---

# Introduction à Hugo et GitHub Pages

Hugo est un générateur de sites statiques rapide et flexible qui vous permet de créer des sites Web sans base de données ni complexité de gestion de serveur. GitHub Pages est un service d'hébergement gratuit offert par GitHub pour publier des sites Web directement depuis des dépôts GitHub.

## Qu'est-ce qu'Hugo ?

Hugo est conçu pour générer des sites Web statiques de manière rapide et efficace. Voici quelques concepts clés :

### 1. Structure de contenu

Hugo utilise une structure de contenu simple basée sur des fichiers Markdown ou d'autres formats de fichier pris en charge. Les fichiers Markdown sont organisés dans des dossiers pour créer la hiérarchie des pages du site.

### 2. Modèles (Templates)

Les modèles définissent la manière dont le contenu est rendu sur le site. Ils utilisent la syntaxe Go et les fichiers HTML pour déterminer la mise en page et la présentation du contenu.

### 3. Thèmes

Les thèmes permettent de personnaliser l'apparence de votre site. Hugo offre la possibilité d'utiliser des thèmes prédéfinis ou de créer les vôtres pour un design spécifique.

### 4. Commandes Hugo

Hugo dispose de nombreuses commandes en ligne pour créer, générer et prévisualiser votre site localement avant de le publier.

## Utilisation de GitHub Pages avec Hugo

GitHub Pages permet d'héberger des sites statiques, y compris ceux créés avec Hugo. Voici les étapes pour publier un site Hugo sur GitHub Pages :

### Étapes :

1. Créez un nouveau dépôt sur GitHub pour votre site.
2. Générez votre site Hugo en local avec la commande `hugo`.
3. Utilisez le dossier `public` généré par Hugo comme dépôt git avec `git init`.
4. Ajoutez, committez et poussez les fichiers sur votre dépôt GitHub.
5. Dans les paramètres de votre dépôt GitHub, configurez GitHub Pages pour utiliser la branche `gh-pages` ou le dossier `/docs` (selon votre configuration).

Une fois ces étapes terminées, votre site Hugo sera accessible via GitHub Pages à l'adresse `https://votre-nom-utilisateur.github.io/nom-de-votre-repo`.