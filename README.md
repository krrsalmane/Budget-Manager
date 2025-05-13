# Budget Manager – Système de Gestion de Budget

**Budget Manager** est une application web RESTful développée par **ENAA TECH** pour permettre aux utilisateurs de gérer leurs finances personnelles de manière efficace. Conçue en Java avec Spring Boot, l'application offre des fonctionnalités clés pour gérer les transactions financières, les budgets par catégorie et les catégories personnalisées. Elle garantit un code fiable et de haute qualité, suivant les meilleures pratiques de développement, pour offrir une expérience utilisateur fluide et sécurisée.

## Contexte du Projet

Dans le cadre de la startup **ENAA TECH**, l'application Budget Manager a été conçue pour répondre aux besoins des utilisateurs souhaitant suivre leurs dépenses et revenus, définir des limites budgétaires par catégorie (alimentation, logement, transport, etc.) et organiser leurs finances via des catégories personnalisées. L'objectif est de fournir une solution intuitive avec une API RESTful robuste, développée selon les standards de qualité logicielle.

## Objectifs du Projet

Budget Manager vise à :
- Permettre aux utilisateurs de suivre leurs transactions financières (dépenses et revenus) avec précision.
- Offrir une gestion flexible des budgets par catégorie pour contrôler les dépenses.
- Permettre la création et la personnalisation de catégories pour organiser les finances.
- Fournir une API RESTful sécurisée et extensible, avec un code fiable et maintenable.

## Fonctionnalités Principales

### Gestion des Transactions
- **Créer** : Ajouter une transaction (montant, catégorie, date, description).
- **Lire** : Consulter la liste des transactions, avec filtres et tris par date, montant ou catégorie.
- **Mettre à jour** : Modifier les détails d’une transaction existante.
- **Supprimer** : Supprimer une transaction si nécessaire.

### Gestion des Budgets
- **Créer** : Définir un budget avec une limite de dépense pour une catégorie spécifique.
- **Lire** : Consulter la liste des budgets, avec limites et montants dépensés par catégorie.
- **Mettre à jour** : Ajuster les limites budgétaires d’une catégorie.
- **Supprimer** : Supprimer un budget obsolète.

### Gestion des Catégories
- **Créer** : Ajouter une catégorie personnalisée pour organiser dépenses et revenus.
- **Mettre à jour** : Modifier une catégorie existante.
- **Supprimer** : Supprimer une catégorie si elle n’est plus nécessaire.

### Diagrams
- ![Diagramme de Classes](![![Capture d'écran 2025-05-12 125021](https://github.com/user-attachments/assets/5809c846-8f8f-44db-988c-66fd16bbcd9b))
- ![Diagramme de Sequence](![!![Capture d'écran 2025-05-12 124253](https://github.com/user-attachments/assets/f5cff7db-dea9-4170-8976-95d84edb3050)
  ))
- ![Diagramme cas de utilisation](![!![Capture d'écran 2025-05-12 124312](https://github.com/user-attachments/assets/721b81a0-f8c7-4d86-ba86-42b9427dd182)
  )
  )

## Technologies Utilisées

- **Backend** : Spring Boot, Spring Data JPA.
- **Langage** : Java.
- **Base de données** : (À spécifier, ex. : MySQL, PostgreSQL, H2 pour les tests).
- **Gestion des dépendances** : Maven.
- **Outils** : Git (contrôle de version), Postman (tests d’API).

## Instructions d’Installation

1. **Cloner le dépôt** :
   ```bash
   git clone https://github.com/votre-repo/budget-manager.git
