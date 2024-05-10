# PROJET SHIFUMI

**Domaine d’application :** Gestion d’une base de données en interaction depuis un site WEB Programmation python d’un jeu en liaison avec la base de données.

## Enoncé du problème

On se propose de créer un site web permettant de jouer gratuitement au jeu pierre-feuille-ciseaux. Pour financer le fonctionnement du site on diffusera des publicités de différents sponsors.

Chaque joueur doit d’abord s’inscrire en donnant nom, prénom, mail (servant d’identifiant) et mot de passe. L’administrateur devra ensuite valider cette inscription avant que le joueur ne puisse s’identifier. Cette validation d’inscription créditera la cagnotte du joueur de 50 écus.

A chaque connexion, une des publicités d’un des sponsors est affichée et la cagnotte sera créditée de 5 écus. Le joueur peut se déconnecter après la publicité sans jouer.

Une fois identifié, le joueur peut démarrer une partie. Il pourra choisir sa mise dans la limite de sa cagnotte et jouer sur cette mise. En cas de victoire, il remporte 2 fois sa mise. En cas d’égalité, la partie continue tant qu’il n’y a pas de vainqueur. Tant que le compte est créditeur, le joueur peut relancer une nouvelle partie.

Une fois connecté (login et mot de passe), l’administrateur pourra consulter et valider les demandes d’inscription en attente.

Sur la page gestion des sponsors, l’administrateur précisera la raison sociale de l’entreprise et l’adresse du site web de cette entreprise si elle existe.

Sur la page de gestion des publicités, l’administrateur pourra ajouter pour une entreprise donnée une ou plusieurs images de publicité en indiquant pour chacune le nombre de diffusion souhaité.

## Taches principales du projet

- Création de la base de données
- Création du programme du jeu Shifumi en python
- Réalisation du site web d’inscription des joueurs, des sponsors, de gestion des publicités
