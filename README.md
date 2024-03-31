
# Yiidein

## Introduction
**Yiidein** est une application web révolutionnaire conçue pour simplifier la prise de rendez-vous en ligne pour une variété de services. Qu'il s'agisse d'une consultation médicale, d'un rendez-vous au salon de beauté, d'une session de bien-être, ou d'une inscription à un cours, Yiidein rend ces démarches plus accessibles et efficaces. Basée sur Spring Boot, Angular, et Bootstrap, cette application offre une expérience utilisateur fluide et intuitive.

## Caractéristiques
- **Large Éventail de Services :** Accès facile à des rendez-vous pour des services publics, des soins médicaux, des séances de bien-être, et bien plus.
- **Interface Utilisateur Intuitive :** Réservez, modifiez, ou annulez des rendez-vous en quelques clics.
- **Notifications et Rappels :** Soyez toujours à jour avec des notifications personnalisées.
- **Gestion de Profil :** Suivez vos rendez-vous passés et à venir facilement.
- **Sécurité et Confidentialité :** Vos informations personnelles sont en sécurité avec nous.

## Démarrage rapide
Pour installer et exécuter Yiidein sur votre système local pour le développement et le test, suivez les étapes ci-dessous :

### Prérequis
- Java JDK 17 ou supérieur
- Node.js et npm
- Angular CLI
- Une instance MySQL

### Installation

1. **Clonez le dépôt :**
```sh
git clone https://github.com/souleymanetimbidiallo/yiidein.git
```

2. **Backend :**
   - Naviguez dans le répertoire backend et installez les dépendances :
     ```sh
     cd yiidein/backend
     ./mvnw clean install
     ```
   - Lancez le serveur Spring Boot :
     ```sh
     ./mvnw spring-boot:run
     ```

3. **Frontend :**
   - Naviguez dans le répertoire frontend et installez les dépendances :
     ```sh
     cd yiidein/frontend
     npm install
     ```
   - Démarrez le serveur de développement Angular :
     ```sh
     ng serve
     ```
   - Ouvrez votre navigateur et allez à `http://localhost:4200`.

## Comment contribuer
Nous accueillons les contributions de tous ! Si vous souhaitez contribuer, veuillez consulter notre `CONTRIBUTING.md` pour plus d'informations sur comment commencer.

## Licence
Yiidein est distribué sous la licence MIT. Voir le fichier `LICENSE` pour plus d'informations.

## Remerciements
Un grand merci à tous ceux qui ont contribué à rendre ce projet possible, y compris (mais sans s'y limiter) les développeurs, les designers, et les testeurs de notre communauté.
