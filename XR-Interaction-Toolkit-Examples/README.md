# Unity XR Interaction Toolkit – Example Project (v2.3)

Ce dépôt contient le **projet d'exemple officiel de Unity** pour le **XR Interaction Toolkit (XRI)** version **2.3**.  
Il a pour objectif d’aider les développeurs à apprendre, tester et implémenter différentes interactions **VR/XR** dans Unity.

---

## 🎯 Description

Ce projet fournit une vue d’ensemble complète des capacités du **XR Interaction Toolkit**, allant des systèmes de locomotion de base aux interactions physiques avancées.

Il inclut plusieurs scènes préconfigurées contenant :
- Des objets interactifs
- Des interfaces utilisateur 3D
- Différents systèmes de déplacement VR

---

## 🚀 Fonctionnalités clés

### 1. Systèmes de locomotion

Plusieurs modes de déplacement sont disponibles et configurables :

- **Mouvement continu & Snap Turn**  
  Paramétrables via un panneau de contrôle en jeu.
- **Téléportation**  
  Avec options de direction d’arrivée.
- **Grab Move**  
  Fonctionnalité introduite avec XRI 2.3 permettant de se déplacer en saisissant le monde.
- **Vignette**  
  Système intégré pour réduire le motion sickness.

---

### 2. Interacteurs et objets

- **XR Grab Interactable**  
  Trois modes de saisie :
  - Instant  
  - Kinematic  
  - Velocity Tracked  
  Compatibles avec les **Direct Interactors** et **Ray Interactors**.
- **Socket Interactors**  
  Zones de placement précis (inventaire, clés, objets interactifs).
- **Contrôles 3D personnalisés**
  - Levier
  - Joystick
  - Bouton rotatif (knob)
  - Curseur (slider)
  - Boutons poussoirs
- **Manipulation à deux mains**  
  Exemples concrets comme la saisie d’une arme à deux mains.

---

### 3. Physique et exemples avancés

- **Jointures physiques**  
  Utilisation de joints pour simuler portes, tiroirs et objets mécaniques.
- **Composants spécifiques**
  - Détection d’inclinaison (*On Tilt*)
  - Détection de vitesse (*On Velocity*)  
  Exemple illustré avec un arrosoir fonctionnel.

---

## 🛠️ Installation

1. **Téléchargement**  
   - Télécharger le projet en ZIP  
   - ou cloner le dépôt via GitHub / GitHub Desktop

3. **Ouverture**
   - Ouvrir Unity Hub
   - Cliquer sur **Open**
   - Sélectionner le dossier du projet
4. **Configuration**
   - Accepter les mises à jour et configurations proposées lors du premier lancement
5. **Exécution**
   - Ouvrir les scènes dans le dossier `Assets/XRI Example Scenes/XRAY_Example_Main`
   - Lancer la scène via le bouton **Play**

---

## 🧭 Scènes à explorer

Le projet est organisé autour de **sept stations thématiques** :

- **XRI Example Scene**  
  Contient les stations individuelles :
  - Locomotion
  - Grab
  - Activate
  - Socket
  - UI
  - Physique
- **XRAY Example Main**  
  Scène principale regroupant toutes les stations dans un environnement complet avec :
  - Montagnes 3D
  - Shaders d’eau
  - Environnement immersif

> **Note** : La démo utilise le prefab de base **XR Origin** avec des contrôleurs standards (sans mains animées).

---

## 📚 Informations complémentaires

Ce README a été rédigé en se basant sur :
- Le **projet d’exemple officiel Unity XR Interaction Toolkit (v2.3)**
- Les tutoriels de la chaîne YouTube **Valem Tutorials** : [https://www.youtube.com/watch?v=dCVAYB2jkEY]

---


