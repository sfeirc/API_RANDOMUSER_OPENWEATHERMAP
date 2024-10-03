# Tableau des utilisateurs

Ce projet affiche un tableau des utilisateurs en utilisant les données de l'API [Random User](https://randomuser.me/) et les données météorologiques de l'API [OpenWeatherMap](https://openweathermap.org/).

## Installation

1. Clonez le dépôt :
    ```sh
    git clone <DEPOT>
    ```
2. Ouvrez le dossier du projet :
    ```sh
    cd <NOM_DU_DOSSIER>
    ```

## Utilisation

1. Ouvrez le fichier `index.html` dans votre navigateur préféré.

## Structure du projet

- `index.html` : Le fichier HTML principal qui contient la structure du tableau.
- `assets/script.js` : Le fichier JavaScript qui récupère les données des API et les affiche dans le tableau.
- `assets/style.css` : Le fichier CSS pour le style du tableau et de la page.
- `assets/img` : Le dossier pour les images des genre 

## Dépendances

- [Tailwind CSS](https://tailwindcss.com/) : Utilisé pour le style du tableau.

## Fonctionnalités

- Récupère les données de l'API Random User.
- Récupère les données météorologiques de l'API OpenWeatherMap.
- Affiche les utilisateurs dans un tableau avec les colonnes suivantes :
  - Nom d'utilisateur
  - Genre
  - Nom
  - Photo
  - Ville
  - Pays
  - Météo (description et température)

## Ressources Externes

- [Random User API](https://randomuser.me/) pour fournir les données des utilisateurs.
- [OpenWeatherMap API](https://openweathermap.org/) pour fournir les données météorologiques.
- [Tailwind CSS](https://tailwindcss.com/) pour le style.
