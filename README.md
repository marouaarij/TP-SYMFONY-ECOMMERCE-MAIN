# 🛒 Projet E-Commerce Symfony

**Réalisé par :** AZZAOUI Fatima Zahra  
**Filière :** Génie Informatique  
**Année universitaire :** 2025-2026  
**Email :** fatimaz.azzaoui0@gmail.com  

---

## 📌 Description

Application e-commerce développée avec le framework **Symfony 8**, suivant une architecture propre et modulaire basée sur les principes **SOLID**.

## 🚀 Fonctionnalités

- 🔐 Authentification (inscription / connexion)
- 🛍️ Catalogue de produits avec pagination
- 📂 Gestion des catégories
- 🛒 Panier d'achat
- 👤 Gestion du profil utilisateur

## 🛠️ Technologies utilisées

- PHP 8.4
- Symfony 8.0
- Doctrine ORM
- MySQL
- Twig
- Bootstrap

## ⚙️ Installation

```bash
composer install
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate
symfony serve
```

## 🏗️ Architecture

Le projet suit le pattern **Interface → Strategy → Handler** avec :
- Services `final readonly`
- DTOs pour les requêtes
- Validation personnalisée