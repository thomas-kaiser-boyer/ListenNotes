# ListenNotes - Application web sécurisée pour stocker et organiser ses notes

Ce projet est une application web sécurisée permettant de stocker et organiser ses notes, accessibles depuis n'importe quel appareil. Elle permet la création et l'édition de notes avec ajout d'images, liens et pièces jointes, ainsi que la synchronisation automatique sur tous les appareils.

### Le contenu de ce repository sera bientôt publié. Merci de votre patience.

## Stack technique

Back-end : Node.js avec Express.js
Front-end : React.js
Base de données : MongoDB avec Mongoose
Authentification : JSON Web Token (JWT)

## Installation

Pour installer et lancer l'application, suivez les étapes suivantes :

### Clonez le repository GitHub :

`git clone https://github.com/thomas-kaiser-boyer/ListenNotes.git`

### Installez les dépendances front-end :

```
cd listennotes
npm install
```
### Installez les dépendances back-end :
```
cd backend
npm install
```
### Lancez la base de données MongoDB :
```
sudo service mongodb start
```
### Créez la base de données et importez les données d'exemple :
```
mongoimport --db listennotes --collection users --file /path/to/listennotes/backend/data/users.json
mongoimport --db listennotes --collection notes --file /path/to/listennotes/backend/data/notes.json
```
### Lancez l'application back-end :
```
cd listennotes/backend
npm start
```
### Lancez l'application front-end :
```
cd listennotes
npm start
```
### L'application devrait maintenant être accessible à l'adresse suivante : http://localhost:3000/

## Fonctionnalités

ListenNotes offre les fonctionnalités suivantes :

* Création et édition de notes, avec la possibilité d'ajouter des images, des liens et des pièces jointes.
* Organisation des notes en dossiers et sous-dossiers, pour une navigation facile et intuitive.
* Recherche de notes par mot-clé, pour retrouver rapidement l'information recherchée.
* Synchronisation automatique des notes sur tous les appareils de l'utilisateur, pour une utilisation en toute mobilité.
* Sécurisation des données utilisateur, grâce à un système d'authentification et de chiffrement de pointe.
