# Kickflip Coding Challenge

## Requis

##### Librairies

- Vous devez utiliser minimalement React, Typescript ainsi que React Testing Library.
- Pour le reste (fetch, state management, styling, etc.), c'est à votre guise.

##### Design

- Le UI / UX est à votre choix, on ne s'attend pas à un chef-d'oeuvre, mais on va regarder le styling un peu.
- Voici un exemple très simple à quoi ça pourrait ressembler:

<img width="1459" alt="Screen Shot 2023-12-11 at 2 00 08 PM" src="https://github.com/fredbegin11/kickflip-coding-challenge/assets/8545738/9a8bbfc1-4193-4944-b56b-37f01632e68a">

## Tâches
### Étape 1

Créer un nouveau projet React avec Typescript. Vous pouvez utiliser create-react-app ou Vite.

### Étape 2

Créer une page qui affiche une liste de recettes de bière.

- Les données doivent provenir de [Brewdog Punk API](https://punkapi.com/documentation/v2) -> `https://api.punkapi.com/v2/beers`
- La liste doit contenir les champs suivants: Name, Tagline, ABV, IBU et Boil Volume

### Étape 3

Ajouter un champs de recherche à la liste. La recherche doit s'effectuer après 1 seconde sans keystroke.

- Le champ recherche doit pouvoir chercher sur le champs Name.

### Étape 4

Ajouter de la pagination à la liste.

- On doit aussi pouvoir choisir le nombre de résultats par page (10, 25 ou 50)

### Étape 5

Ajouter un test unitaire pour la fonctionnalité de recherche en utilisant React Testing Library

### Étape 6

Push l'exercice sur votre github personnel et m'envoyer les accès par email

Bon test!
