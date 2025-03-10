# Plateforme de Gestion RH - Frontend

![Statut du projet](https://img.shields.io/badge/statut-en%20cours-blue)
![Licence](https://img.shields.io/badge/licence-MIT-green)

## Aperçu
Ceci est le frontend d'une plateforme de gestion des ressources humaines (RH), développée uniquement avec HTML et CSS. Elle fournit des pages essentielles pour l'authentification, la gestion des employés et les fonctionnalités du tableau de bord.

## Structure du projet
Le projet est organisé en différents dossiers afin de maintenir un code propre et structuré. Voici l'arborescence du projet :

```
HR-Management-Platform/
│── index.html
│── assets/
│   ├── css/
│   │   ├── styles.css
│   │   ├── auth.css
│   │   ├── dashboard.css
│   ├── images/
│── authentification/
│   ├── login.html
│   ├── register.html
│── dashboard/
|   ├──gestion-administrative/
│   ├── dashboard.html      |──presence
│   ├── employees.html      |──permission
│   ├── settings.html       |──accident
│   ├── reports.html        
│── README.md
```

## Description des fichiers

### Fichiers racine
- **index.html** : Page d'accueil qui présente une vue d'ensemble de la plateforme et un bouton de connexion/inscription.

### Assets
- **css/** : Contient tous les fichiers CSS pour le style des différentes parties de la plateforme.
- **images/** : Stocke toutes les images utilisées dans la plateforme.
- **fonts/** : Contient les polices personnalisées utilisées dans le design.

### Pages d'authentification (`auth/`)
- **login.html** : Page de connexion pour les utilisateurs.
- **register.html** : Page d'inscription pour créer un compte.
- **forgot-password.html** : Permet aux utilisateurs de réinitialiser leur mot de passe en cas d'oubli.

### Pages du tableau de bord (`dashboard/`)
- **dashboard.html** : Page principale du tableau de bord après connexion.
- **employees.html** : Liste des employés avec des fonctionnalités de gestion.
- **settings.html** : Permet aux utilisateurs de mettre à jour leurs paramètres de profil.
- **reports.html** : Fournit des analyses et rapports relatifs à la gestion RH.

## Comment utiliser
1. Ouvrir `index.html` dans un navigateur pour accéder à la page d'accueil.
2. Naviguer vers les pages d'authentification (`auth/`) pour se connecter ou s'inscrire.
3. Une fois connecté, accéder aux pages du tableau de bord (`dashboard/`) pour gérer les fonctions RH.

## Notes
- La plateforme est statique (HTML & CSS uniquement) et ne comprend aucune fonctionnalité backend.
- Pour ajouter des interactions et une validation de formulaire, l'intégration de JavaScript est recommandée.

## Aperçu Visuel
Ajoutez ici les liens vers les captures d'écran de l'application :

![Aperçu 1](./assets/images/capture1.png)
![Aperçu 2](./assets/images/capture2.png)
![Aperçu 3](./assets/images/capture3.png)
![Aperçu 4](./assets/images/capture4.png)
![Aperçu 5](./assets/images/capture5.png)
![Aperçu 6](./assets/images/capture6.png)
![Aperçu 7](./assets/images/capture7.png)
![Aperçu 8](./assets/images/capture8.png)
![Aperçu 9](./assets/images/capture9.png)
![Aperçu 10](./assets/images/capture10.png)
![Aperçu 11](./assets/images/capture11.png)

## Contributeurs
- **Kouawou Alex Russel** - [Email](alex-russel.kouawou@epitech.eu)
- **Gossou Romeo** - [Email](romeo.gossou-bah@epitech.eu)
- **Afedjou Stone** - [Email](stone.afedjou@epitech.eu)
- **Brandon Daniel MEDEHOU** - [Email](brandonmedehou2203@gmail.com)


