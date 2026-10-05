# Ahamada-mze
site web
 Mon École V2 — plateforme fonctionnelle

## Ce que cette V2 ajoute
- Serveur Node.js + Express
- Authentification avec mots de passe hachés
- Sessions de connexion
- Données conservées côté serveur dans `data.json`
- Interface professeur
- Interface élève
- Création, modification et suppression de cours
- Diaporamas
- QCM
- Progression par élève
- Création de comptes élèves
- Attribution de devoirs
- Interface responsive téléphone/ordinateur

## Installation
Il faut Node.js installé.

Dans le dossier du projet :

```bash
npm install
npm start
```

Puis ouvrir :
http://localhost:3000

## Comptes de démonstration
Professeur :
- identifiant : prof
- mot de passe : 1234

Élève Léa :
- identifiant : lea
- mot de passe : 1234

Élève Sarah :
- identifiant : sarah
- mot de passe : 1234

## Mise en ligne
Cette version peut être déployée sur un hébergeur Node.js. Pour une vraie utilisation familiale en production, il faut remplacer le stockage JSON par une base de données (par exemple PostgreSQL/Supabase), utiliser HTTPS, une vraie variable SESSION_SECRET et renforcer les règles de sécurité.

## Important
Les comptes de démonstration et le mot de passe `1234` sont uniquement pour les tests. Change-les avant une utilisation réelle.
