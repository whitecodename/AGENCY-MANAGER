# Module de Gestion d'Agences de Voyage

## Introduction

Le module de gestion d'agences de voyage est conçue pour aider les agences de voyage à gérer efficacement leurs opérations quotidiennes, y compris la gestion des voyages, des conducteurs, des réservations et des centres de déploiement. Ce module fournit une interface intuitive et des fonctionnalités robustes pour assurer une gestion fluide et organisée.

Voici une version complétée et arrangée des fonctionnalités de notre module :

## Fonctionnalités

- **Gestion des voyages :**
  - **Ajouter un voyage :** Créer un enregistrement de voyage avec des informations de base.
  - **Planifier un voyage :** Détaillez et finalisez les aspects logistiques du voyage, tels que les horaires, les conducteurs et les véhicules.
  - **Publier un voyage :** Rendre le voyage disponible pour les réservations des clients.
  - **Modifier un voyage :** Mettre à jour les informations et les détails logistiques d'un voyage.
  - **Supprimer un voyage :** Retirer un voyage du système.

- **Gestion des conducteurs :**
  - **Ajouter un conducteur :** Ajouter les informations d'un nouveau conducteur dans le système.
  - **Modifier un conducteur :** Mettre à jour les informations d'un conducteur existant.
  - **Supprimer un conducteur :** Retirer un conducteur du système.
  - **Rechercher des conducteurs :** Trouver des conducteurs disponibles en fonction de divers critères (par exemple, disponibilité, expérience).

- **Gestion des réservations :**
  - **Confirmer une réservation :** Valider une réservation soumise par un client.
  - **Rejeter une réservation :** Refuser une réservation soumise par un client.
  - **Rechercher des réservations :** Trouver des réservations en fonction de divers critères (par exemple, date, destination).
  - **Soumettre une réservation :** Réserver un voyage proposé par une agence.
  - **Annuler une réservation :** Supprimer une réservation existante.

- **Gestion des centres de déploiement :**
  - **Ajouter un centre de déploiement :** Ajouter un nouveau centre de déploiement dans le système.
  - **Modifier un centre de déploiement :** Mettre à jour les informations d'un centre de déploiement existant.
  - **Supprimer un centre de déploiement :** Retirer un centre de déploiement du système.
  - **Rechercher des centres de déploiement :** Trouver des centres de déploiement disponibles en fonction de divers critères.

- **Gestion des agences de voyage :**
  - **Ajouter une agence de voyage :** Créer une nouvelle agence de voyage dans le système.
  - **Modifier une agence de voyage :** Mettre à jour les informations d'une agence de voyage existante.
  - **Supprimer une agence de voyage :** Retirer une agence de voyage du système.
  - **Rechercher des agences de voyage :** Trouver des agences de voyage existantes en fonction de divers critères.
  - **Noter une agence de voyage :** Donner une note à une agence de voyage en fonction de l'expérience de voyage.
  - 
## Prérequis

- [Node.js](https://nodejs.org/) (version 14.x ou supérieure)
- [npm](https://www.npmjs.com/) (version 6.x ou supérieure)
- [ScyllaDB](https://www.scylla.com/) (pour la base de données)

## Installation

1. Clonez le dépôt :
    ```bash
    git clone https://github.com/whitecodename/TRAVEL-AGENCY-repo.git
    cd TRAVEL-AGENCY
    ```

2. Installez les dépendances du module :
    ```bash
    npm install
    ```

## Démarrage

1. Démarrer l'api :
    ```bash
    ./mvnw spring-boot:run
    ```

2. Démarrer la vue :
    ```bash
    npm start
    ```
    
4. Ouvrez votre navigateur et accédez à `http://localhost:3000`.

## License

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.

## Auteurs

- [BENGONO NATHAN](https://github.com/Nathan10amvela) (CHEF DU PROJET)
- [BENGONO NATHAN](https://github.com/yohanpy2004)
- [SOLEFACK KROS](https://github.com/krostemgoua)
- [VUIDE JORDAN](https://github.com/whitecodename)

## Remerciements

- Merci au professeur DJOTIO, notre professeur titulaire ainsi que notre chargé de TD Monsieur KUITCHE qui nous ont accompagné dans la réalisation de ce projet.
