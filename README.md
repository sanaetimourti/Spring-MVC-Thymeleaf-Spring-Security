# Spring-MVC-Thymeleaf-Spring-Security


Projet Spring MVC avec Thymeleaf et Spring Security .

## Description

Application web de gestion de produits avec authentification et autorisation utilisant Spring Security.

## Technologies utilisées

- Spring Boot 3.4.5
- Spring MVC
- Spring Data JPA
- Spring Security
- Thymeleaf
- H2 Database
- MySQL (optionnel)
- Bootstrap 5.3.5
- Lombok
- Maven

## Prérequis

- Java 21
- Maven 3.x

## Installation

1. Cloner le repository:
```bash
git clone https://github.com/sanaetimourti/Spring-MVC-Thymeleaf-Spring-Security.git
cd spring-mvc-enset
```

2. Compiler le projet:
```bash
./mvnw clean install
```

3. Lancer l'application:
```bash
./mvnw spring-boot:run
```

L'application sera accessible sur `http://localhost:8094`

## Utilisateurs par défaut

- **Utilisateur 1**: `user1` / `1234` (ROLE_USER)
- **Utilisateur 2**: `user2` / `1234` (ROLE_USER)
- **Administrateur**: `admin` / `1234` (ROLE_USER, ROLE_ADMIN)

## Fonctionnalités

- Authentification et autorisation avec Spring Security
- Gestion des produits (CRUD)
- Interface utilisateur avec Thymeleaf et Bootstrap
- Base de données H2 en mémoire
- Console H2 accessible sur `/h2-console`

## Structure du projet

```
src/
├── main/
│   ├── java/
│   │   └── net/
│   │       └── enset/
│   │           └── bdccensetspringmvc/
│   │               ├── entities/
│   │               ├── repsoitory/
│   │               ├── sec/
│   │               └── web/
│   └── resources/
│       ├── templates/
│       └── application.properties
└── test/
```
