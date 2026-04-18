Projet APO – Jeux de société au tour par tour
---

 - Description

Ce projet a été réalisé dans le cadre du module APO (Algorithmique et Programmation Orientée Objet).
Il s’agit d’un moteur de jeux de société au tour par tour, extensible et modulaire, permettant de jouer à plusieurs jeux via une interface console ou graphique.

Le projet met en œuvre les principes de la programmation orientée objet ainsi qu'une architecture MVC.

---
 - Jeux implémentés

-- Tic-Tac-Toe (2D)

-- Tic-Tac-Toe 3D

-- Puissance 4

-- Échecs

---
 - Architecture

Le projet est structuré selon le motif Modèle – Vue – Contrôleur (MVC) :

Modèle : logique métier, règles des jeux, plateau, pièces

Vue : affichage console et interface graphique

Contrôleur : gestion des interactions utilisateur

Les règles de déplacement des pièces sont gérées à l’aide du patron de conception Décorateur, permettant de composer dynamiquement des comportements sans modifier le code existant.

 - Technologies utilisées

Java 25

Maven (gestion de la compilation et des dépendances)

Interface graphique Java (Swing)

Tests unitaires JUnit

 - Lancer le projet
Prérequis

Java 25 installé

Maven installé

Compilation et tests
mvn clean install

Lancement de l’application
mvn exec:java

 - Tests

Plusieurs tests unitaires ont été implémentés afin de vérifier le bon fonctionnement des modules principaux du projet.
Ils sont exécutés automatiquement lors de la commande mvn clean install.

 - Auteurs

Projet réalisé en groupe de 3 :

Mohamed Amine Guesmi

Yassine Razi

Mattéo Chauchet

---
 - Contexte académique

Projet réalisé à Polytech Lyon – INFO 3A
Année universitaire 2025–2026
