# API REST Gestion de Voitures Classiques

API REST pour gérer une collection de voitures classiques.
Développée avec Node.js, Express et SQLite.

## Prérequis
- Node.js (v16 ou supérieure)
- npm ou yarn
- Postman (pour tester l'API)

## Installation

1. Cloner le projet
   ```bash
   git clone https://github.com/houssein931/car-api/
   cd car-api


## Authentification
Toutes les routes API nécessitent une clé API dans les headers :

Key: x-api-key

Value: ma-super-cle-api-2024

## commande postman

GET /api/cars
Récupère toutes les voitures.

GET /api/cars/:id
Récupère une voiture par son ID.

POST /api/cars
Crée une nouvelle voiture. Body (JSON)

PUT /api/cars/:id
Modifie une voiture existante.

DELETE /api/cars/:id
Supprime une voiture.

## Technologies utilisées
Node.js: Environnement d'exécution JavaScript

Express: Framework web minimaliste

SQLite3: Base de données légère

Cors: Gestion des requêtes cross-origin