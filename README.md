# Gestion Employe

## Description

Cette application est une **application hybride (mobile et web)** développée avec React Native (Expo).
Elle permet de gérer une liste d’employés, calculer leurs salaires et visualiser des statistiques sous forme de graphiques.

---

## Objectifs

* Gérer les employés (CRUD)
* Calculer automatiquement les salaires
* Afficher des statistiques (total, min, max)
* Visualiser les données avec des graphiques
* Utiliser une base de données distante (PostgreSQL)

---

## Technologies utilisées

### Frontend

* React Native (Expo)
* FlatList
* React Navigation
* React Native Chart Kit

### Backend

* Express (API REST)

### Base de données

* PostgreSQL

---

## Structure du projet

```
employee-management/
│
├── assets/
├── src/
│   ├── components/
│   ├── screens/
│   ├── navigation/
│   ├── services/
│   ├── utils/
│   ├── constants/
│
├── App.js
├── package.json
└── README.md
```

---

## Fonctionnalités

### Gestion des employés

* Ajouter un employé
* Afficher la liste des employés
* Modifier un employé
* Supprimer un employé

---

### Calcul des salaires

* Salaire = Nombre de jours × Taux journalier
* Calcul automatique pour chaque employé

---

### Statistiques

* Salaire total
* Salaire minimum
* Salaire maximum

---

### Visualisation graphique

* Histogramme (Bar Chart)
* Camembert (Pie Chart)

---

## Écrans de l’application

* HomeScreen : Liste des employés + statistiques
* AddEmployeeScreen : Ajouter un employé
* EditEmployeeScreen : Modifier un employé
* ChartScreen : Visualisation graphique

---

## API (Backend)

### Endpoints disponibles :

* `GET /employes` → récupérer les employés
* `POST /employes` → ajouter un employé
* `PUT /employes/:id` → modifier un employé
* `DELETE /employes/:id` → supprimer un employé

---

## Installation

### 1. Cloner le projet

```
git clone https://github.com/florida0101/Gestion-Employe.git
cd Gestion-Employe
```

### 2. Installer les dépendances

```
npm install
```

### 3. Lancer le projet

```
npx expo start
```

---

## 📲 Exécution

* Mobile : scanner le QR code avec Expo Go
* Web :

```
npm run web
```

---

## 📊 Calcul des statistiques

Les statistiques sont calculées à partir des salaires :

```
Salaire = nombreJours * tauxJournalier
```

---

## 👨‍💻 Auteur

Projet réalisé dans le cadre d’un projet scolaire de développement d’une application hybride.
