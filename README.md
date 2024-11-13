# Twitch Bootstrap Clone

## Description

Ce projet est un clone d'une interface de type Twitch créé à l'aide de HTML, CSS et Bootstrap. L'objectif est de recréer la mise en page et les fonctionnalités visuelles essentielles d'une plateforme de streaming. Le projet vise à donner un aperçu de l'apparence et du fonctionnement d'un site de streaming en utilisant les capacités de Bootstrap pour garantir une adaptabilité et une esthétique moderne.

## Fonctionnalités

- **Barre de navigation adaptative** : Une barre de navigation qui inclut des liens vers différentes sections telles que "Parcourir", "Esports" et "Musique". Les liens ne sont apas opérationnels.
- **Modal d'abonnement** : Une modale d'abonnement avec trois niveaux d'abonnement différents qui apparaît au clic du bouton s'abonner.
- **Barre latérale gauche** : Une liste de chaînes recommandées affichée dans une barre latérale fixe, fournissant des informations supplémentaires sur les streamers, comme le nombre actuel de spectateurs.
- **Zone de contenu principal** : Contenu vidéo intégré (utilisant YouTube comme espace réservé) et informations relatives au flux vidéo, telles que son titre, les détails du streamer, et les diffusions récentes.
- **Styles personnalisés** : Utilisation de styles personnalisés pour améliorer l'apparence, y compris un schéma de couleurs unique et des styles de boutons alignés avec le thème de la marque Twitch.

## Stack technique

- **HTML** : Structure le contenu de la page.
- **CSS** : Styles personnalisés pour adapter les composants Bootstrap et rendre la page unique.
- **Bootstrap** : Assure la réactivité et fournit des composants d'interface utilisateur prêts à l'emploi.
- **Paramètres JSON** : Le projet inclut des paramètres pour le serveur en direct afin de simplifier le développement local.

## Pour commencer

### Prérequis

Pour exécuter le projet en local, vous aurez besoin de :

- Un navigateur web moderne.
- Un éditeur de code (comme VS Code).
- L'extension [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) installée dans votre éditeur de code pour prévisualiser le projet.

### Installation

1. **Clonez le dépôt** :

   ```sh
   git clone https://github.com/pricilliaedou/Bootstrap-Twitch.git
   ```

2. **Accédez au répertoire du projet** :

   ```sh
   cd Bootstrap-Twitch
   ```

3. **Ouvrez le projet dans votre éditeur de code et lancez le serveur en direct**.

### Exécution du Projet

- Lancez un serveur en direct depuis votre éditeur de code pour voir le projet dans votre navigateur.
- Ouvrez `index.html` pour explorer l'interface de type Twitch.

## Structure du Projet

- **index.html** : Le fichier HTML principal contenant la structure de la page.
- **css/style.css** : Contient tous les styles personnalisés pour le projet, remplaçant les paramètres par défaut de Bootstrap pour obtenir l'apparence souhaitée.
- **settings.json** : Paramètres de configuration pour le serveur en direct.

## Démo du projet

https://bootstrap-twitch.netlify.app

## Licence

Ce projet est open-source et disponible sous la licence MIT. N'hésitez pas à le fork et à le modifier pour vos besoins.
