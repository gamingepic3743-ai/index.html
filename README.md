# 🌐 Cyber Human Warfare

[![Three.js](https://img.shields.io/badge/Three.js-r128-00ffff?style=flat-square&logo=three.js)](https://threejs.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

Un jeu de tir à la première personne (FPS) de type **Battle Royale** au style cyberpunk, entièrement développé en HTML5, CSS3 et 3D avec la bibliothèque **Three.js**. Affrontez des bots humanoïdes redoutables au cœur d'une forêt virtuelle et survivez au rétrécissement inexorable de la zone !

---

## 🎮 Fonctionnalités du Jeu

* **Arène Dynamique (Battle Royale) :** Une zone laser cylindrique se rétrécit en temps réel. Restez à l'intérieur sous peine de subir des dégâts critiques.
* **Adversaires Humanoïdes :** 9 bots autonomes qui patrouillent, traquent le joueur et tirent à vue dès qu'il est à portée.
* **Arsenal Varié & Système de Loot :** Ramassez différentes armes dispersées au sol (Laser 🟢, Plasma 🟣, CyberSMG 🟡, Pompe 🔴) possédant chacune leurs propres caractéristiques de cadence, dégâts et vitesse de projectile.
* **Gestion d'Inventaire (Hotbar) :** Portez jusqu'à 3 armes en même temps et gérez vos consommables de survie.
* **Consommables Fonctionnels :** Ramassez et utilisez des kits de soin (Slot 4) et des potions d'armure (Slot 5) en faisant un clic gauche pour régénérer vos points de vie et votre bouclier.
* **Effets Audio Intégrés :** Sons de tirs et de ramassage générés dynamiquement via l'API *AudioContext* (aucun fichier audio externe requis).

---

## 🕹️ Commandes du Jeu

| Touche(s) | Action |
| :--- | :--- |
| **Z, Q, S, D** | Se déplacer (Avant, Gauche, Arrière, Droite) |
| **Souris** | Visée (Caméra à la première personne) |
| **Clic Gauche** | Tirer (Armes) / Consommer (Soin ou Armure) |
| **MAJ (Shift)** | Sprinter (Consomme de la jauge d'Énergie) |
| **ESPACE** | Sauter |
| **R** | Recharger l'arme active |
| **Molette / Clavier (&, é, ", ', ()** | Changer de slot d'inventaire (Slots 1 à 5) |

---

## 🚀 Comment lancer le projet localement ?

Le jeu est entièrement autonome (*statique*) et ne nécessite aucune installation de serveur complexe.

1. Téléchargez ou clonez ce dépôt sur votre machine.
2. Assurez-vous que le fichier principal est nommé `index.html`.
3. Double-cliquez simplement sur le fichier `index.html` pour l'ouvrir dans votre navigateur web (Chrome, Firefox, Edge, Safari).
4. Cliquez sur **"ENTRER DANS L'ARÈNE"** et survivez !

---

## 🛠️ Technologies Utilisées

* **HTML5 / CSS3** : Structure globale et interface utilisateur (HUD, menus de démarrage et de fin).
* **JavaScript (ES6+)** : Logique du jeu, mouvements, IA des bots et gestion des collisions.
* **Three.js (r128)** : Moteur 3D pour le rendu de la scène, des arbres, des projectiles et des personnages humanoïdes.

---

## 📝 Licence

Ce projet est sous licence MIT. Vous pouvez librement le cloner, le modifier et partager vos propres versions !
