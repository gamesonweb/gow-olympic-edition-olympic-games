# Projet Games On Web 2024 : Olympic Games
# Sommaire :
- [Introduction](#introduction)
	- [Condition de Participation](#condition-de-participation)
	- [Formations participantes au concours](#formations-participantes-au-concours)
	- [Présentation du Candidat](#présentation-du-candidat)
- [Jeu d'athlétisme](#jeu-dathlétisme)
	- [But](#but)
	- [Difficulté](#difficulte)
- [Jeu de Haies](#jeu-de-haies)
	- [But](#but-1)
	- [Difficulté](#difficulte-1)
- [Jeu de lancer de poids](#jeu-de-lancer-de-poids)
	- [But](#but-2)
	- [Difficulté](#difficulte-2)
- [Jeu de Natation](#jeu-de-natation)
	- [But](#but-3)
	- [Difficulté](#difficulte-3)
- [Conception](#conception)
	- [Menu de Navigations](#menu-de-navigations)
	- [Classes du Jeu](#classes-du-jeu)
	- [Conception Architecture Fichier](#conception-architecture-fichier)


# Introduction :

## Condition de Participation :

### Formations participantes au concours:

- Licences et Masters Miage, Informatique et autres des Universités Côte d'Azur, Aix Marseille, et Paul Sabatier Toulouse 3

- IUT Nice Côte d'Azur et Aix-Marseille,

- Polytech Nice-Sophia,




### Objectifs :

Par équipe, vous devez programmer votre propre jeu 3D, il devra être exécutable dans un navigateur web à jour et développé à l'aide des langages HTML / CSS / Javascript et du framework open source BabylonJS facilitant la programmation des jeux 3D. Toute autre librairie ou framework 3D est interdite. Néanmoins l’usage de librairies utilitaires est permis. Le thème à respecter est "Olympic Edition".


### Le livrable devra obligatoirement contenir :


- Le code source du projet dans son intégralité

- Une description détaillée de votre jeu

- Une vidéo de 30s de gameplay

- L'URL sur laquelle tester le jeu (le jeu devra être mis en ligne)

- Attention : Aucun projet ne sera accepté après le 12 mai 2024 à minuit.


### Prix et lots :

Les participant(e)s / gagnant(e)s se verront attribuer des prix en fonction des résultats de l’évaluation des projets par l’Organisateur :

Le top du top : podium des 3 meilleurs jeux

- Prix du jeu le plus original

- Prix coup de cœur CGI

- Prix coup de pouce

- Prix de la performance technique

- Plus de 10 000€ de lots à gagner, parmi lesquels : accessoires pour gamers, consoles, drones, et bien plus...


Chaque participant(e) qui remet un projet sera récompensé(e).





## Présentation du Jeu et du Projet :

Olympic-Games est un jeu en 3D qui intègre quatre mini-jeux inspirés des Jeux Olympiques :

- Athlétisme
- Natation
- Lancer de poids
- Saut de haies

Ces mini-jeux utilisent un système interactif de jauges et de touches du clavier à activer précisément au bon moment. Les joueurs peuvent relever des défis à divers niveaux de difficulté en affrontant des adversaires gérés par intelligence artificielle, adaptés pour offrir un challenge progressif et engageant.





## Présentation du Candidat :

Je suis Mahjoub Lemine, actuellement engagé dans un parcours d'apprentissage en alternance, poursuivant ma première année de BUT en Informatique.

En tant qu'unique membre de mon équipe, je prends en charge toutes les responsabilités et défis liés à mon projet, de la documentation. a la conception, a l’implémentation.


# Jeu d'athlétisme :

## But :

Le jeu d'athlétisme est un mini-jeu qui simule une course de sprint. Le joueur doit appuyer sur la touche de clavier indiquée à l'écran pour faire avancer son personnage. Le but est de franchir la ligne d'arrivée en un temps record.

## Difficulté :

- Facile : Ennemis relativement lents, jauge pas très dure, les touches pressées font accélérer beaucoup le joueur, les erreurs de touches ne font pas ralentir le joueur.

- Intermediaire : Ennemis relativement lents, jauge assez dure, les touches pressées font moins accélérer, les erreurs de touches entraînent des pénalités de 0.5s.

- Difficile : Ennemis plus rapides, jauge dure, les touches pressées font moins accélérer, les touches entraînent des pénalités de 1s.


# Jeu de Haies :

## But :

Le jeu de haies est un mini-jeu qui simule une course de haies. Le joueur doit appuyer sur la touche de clavier indiquée à l'écran pour faire sauter son personnage. Le but est de franchir la ligne d'arrivée en un temps record.

## Difficulté :

- Facile : Ennemis ratant beaucoup, pénalité de saut -> 0.5s

- Intermediaire : Ennemis avec un taux de ratage de 15%, rapidité augmentée, pénalité de saut -> 0.5s

- Difficile : Ennemis avec un taux de ratage de 5%, rapidité encore plus augmentée, pénalité de saut -> 1s


# Jeu de lancer de poids :

## But :

Le jeu de lancer de poids est un mini-jeu qui simule une compétition de lancer de poids. Le joueur doit appuyer sur la touche de clavier indiquée à l'écran pour lancer le poids. Le but est de lancer le poids le plus loin possible.

## Difficulté :

- Facile : Jauge de lancer facile

- Intermediaire : Jauge de lancer moyenne

- Difficile : Jauge de lancer difficile

# Jeu de Natation :

## But :

Le jeu de natation est un mini-jeu qui simule une course de natation. Le joueur doit appuyer sur la touche de clavier indiquée à l'écran pour faire avancer son personnage. Le but est de franchir la ligne d'arrivée en un temps record.

## Difficulté :

- Facile : Ennemis relativement lents, jauge pas très dure, les touches pressées font accélérer beaucoup le joueur, les erreurs de touches ne font pas ralentir le joueur.

- Intermediaire : Ennemis relativement lents, jauge assez dure, les touches pressées font moins accélérer, les erreurs de touches entraînent des pénalités de 0.5s.

- Difficile : Ennemis plus rapides, jauge dure, les touches pressées font moins accélérer, les touches entraînent des pénalités de 1s.


# Conception :

## Menu de Navigations :

![alt text](navigation.png)

## Classes du Jeu :

![alt text](classe.png)

## Conception Architecture Fichier :

- lib : contient les fichiers contenant les librairies et classes utilisées
  - HUD : contient les fichiers de la classe HUD
  - Scene : contient les fichiers de la classe Scene
  - Player : contient les fichiers de la classe Player
- app.js : fichier principal du jeu
- style.css : fichier de style du jeu
- index.html : fichier d'entrée du jeu

Lemine Mahjoub

Bon README présentant votre équipe, votre projet, vos galères, vos satisfactions, des screenshots, vidéos possibles ici aussi.
