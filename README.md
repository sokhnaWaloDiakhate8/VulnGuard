VulnGuard

Intelligent Vulnerability Management Platform

Description

VulnGuard est une plateforme web de gestion des vulnérabilités permettant aux organisations de découvrir, analyser, prioriser et suivre les vulnérabilités de leurs actifs informatiques.

L'objectif est d'offrir une vue centralisée du niveau de sécurité d'un système d'information tout en facilitant le suivi des actions de remédiation.



Objectifs

- Centraliser les actifs informatiques
- Découvrir automatiquement les équipements du réseau
- Scanner les vulnérabilités
- Prioriser les risques
- Suivre les remédiations
- Générer des rapports
- Fournir des tableaux de bord de sécurité



Fonctionnalités

Gestion des utilisateurs
- Authentification sécurisée
- Gestion des rôles
- Contrôle d'accès (RBAC)

Gestion des actifs
- Inventaire des équipements
- Classification des actifs
- Gestion de la criticité

Découverte réseau
- Scan réseau avec Nmap
- Découverte automatique des hôtes
- Détection des ports et services

Gestion des vulnérabilités
- Intégration avec Greenbone/OpenVAS
- Gestion des CVE
- Priorisation basée sur le risque

Remédiation
- Affectation des tâches
- Suivi des corrections
- Historique des actions

Reporting
- Tableau de bord
- Rapports PDF
- Statistiques

Architecture

Le projet est organisé selon une architecture inspirée de la Clean Architecture


Frontend (React)

↓

REST API

↓

Application Services

↓

Domain Layer

↓

Infrastructure Layer

↓

PostgreSQL + Nmap + Greenbone




Technologies

Frontend
- React
- Tailwind CSS
- React Router

Backend
- Node.js
- Express.js
- JWT
- bcrypt

Base de données
- PostgreSQL

Sécurité
- Nmap
- Greenbone/OpenVAS

DevOps
- Docker
- Docker Compose
- GitHub Actions (à venir)



Structure du projet


VulnGuard/
│
├── backend/
├── frontend/
├── docs/
├── docker/
├── scripts/
└── README.md


Documentation

La documentation du projet est disponible dans le dossier docs/.

Elle comprend :

- Cahier des charges
- Analyse des besoins
- Diagrammes UML
- Architecture
- Modèle de données
- Documentation API
- Documentation technique



Feuille de route

- [x] Cadrage du projet
- [x] Cahier des charges
- [x] Analyse des besoins
- [ ] Diagrammes UML
- [ ] Conception de la base de données
- [ ] Développement Backend
- [ ] Développement Frontend
- [ ] Intégration Nmap
- [ ] Intégration Greenbone
- [ ] Tableau de bord
- [ ] Déploiement Docker



Équipe

Développé par : Sokhna Walo DIAKHATE

Projet réalisé dans le cadre d'un projet professionnel en cybersécurité.

Licence

Ce projet est distribué sous la licence MIT.
