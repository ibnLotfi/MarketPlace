# Marketplace

Plateforme web de petites annonces inspirée des plateformes comme Leboncoin.

Projet personnel développé avec **.NET / C# et Angular**, avec une attention particulière portée à l'architecture, la qualité du code, les performances, la sécurité et les bonnes pratiques de développement.

## Fonctionnalités

### MVP

* [ ] Consulter les annonces
* [ ] Consulter le détail d'une annonce
* [ ] Parcourir les catégories et sous-catégories
* [ ] Rechercher une annonce
* [ ] Pagination et tri

### V0.2 — Recherche avancée

* [ ] Filtrer par localisation
* [ ] Filtrer par distance
* [ ] Filtres spécifiques aux catégories
* [ ] Filtrer par prix
* [ ] Recherche multi-critères

### V0.3 — Comptes et annonces

* [ ] Inscription / connexion
* [ ] Authentification et autorisation
* [ ] Publier une annonce
* [ ] Modifier une annonce
* [ ] Supprimer une annonce
* [ ] Modération des annonces

### V0.4 — Messagerie

* [ ] Contacter un vendeur
* [ ] Conversations privées
* [ ] Historique des messages
* [ ] Messages lus / non lus

## Architecture

Monolithe structuré selon les principes de **Clean Architecture**.

```text
src/
├── Marketplace.Api
├── Marketplace.Application
├── Marketplace.Domain
└── Marketplace.Infrastructure

tests/
├── Marketplace.UnitTests
└── Marketplace.IntegrationTests
```

## Stack

**Backend**

* C#
* .NET / ASP.NET Core
* Entity Framework Core

**Frontend**

* Angular
* TypeScript

**Database**

* SQL Server

**Tests**

* xUnit

**DevOps**

* Docker
* GitHub Actions

## Concepts techniques

Le projet met notamment en œuvre :

* Clean Architecture
* SOLID
* Design Patterns
* Entity Framework Core
* Authentication & Authorization
* Logging
* Caching
* Gestion des exceptions
* Tests
* Optimisation et performance

## Statut

🚧 Projet en cours de développement.

**Version actuelle : v0.1 — MVP**
