# Jeu Pong en Java

## Description
Ce projet est une **reproduction du jeu Pong** développée en **Java** à l’aide de l’environnement **Eclipse**.  
Il s’agit d’un projet personnel visant à renforcer mes compétences en **programmation orientée objet**, en **gestion des événements** et en **conception de jeux 2D**.

Le jeu oppose deux joueurs (ou un joueur et un second contrôlé manuellement) qui déplacent leurs raquettes verticalement pour renvoyer la balle et marquer des points.

---

## Fonctionnalités principales
- Mouvement fluide des raquettes avec les touches :
  - Joueur 1 → `W` (haut) et `S` (bas)
  - Joueur 2 → flèches `↑` et `↓`
- Balle rebondissant sur les murs et les raquettes
- Système de score dynamique affiché à l’écran
- Interface graphique simple via **Java AWT** et **Swing**
- Boucle de jeu temps réel avec gestion de la physique (vitesse, direction, collisions)
- Architecture modulaire (classes distinctes : `Ball`, `Paddle`, `Score`, `GamePanel`, etc.)

---

## Technologies utilisées
- **Langage :** Java  
- **IDE :** Eclipse  
- **Librairies :** AWT, Swing  
- **Paradigme :** Programmation orientée objet  
- **Structure du projet :**
  - `Ball.java` → Gère la balle et ses mouvements  
  - `Paddle.java` → Gère les raquettes  
  - `Score.java` → Affiche et met à jour les scores  
  - `GamePanel.java` → Gère la logique du jeu et le rendu  
  - `GameFrame.java` → Configure la fenêtre principale  
  - `PongGame.java` → Point d’entrée du programme  

---

## Installation et exécution

### Pré-requis :
- **Java JDK 8+**
- **Eclipse IDE** ou tout autre environnement compatible Java

###  Exécution :
1. Télécharger le projet ou le cloner :
   ```bash
   git clone https://github.com/tonpseudo/PongGame.git
