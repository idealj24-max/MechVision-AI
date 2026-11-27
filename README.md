# ⚙️ MechVision AI — Industrial CAD & Reverse Engineering PWA

**MechVision AI** est une application web progressive (PWA) mobile-first conçue pour les ateliers de maintenance, les techniciens de terrain et les ingénieurs. Elle permet de transformer instantanément une photo de pièce mécanique ou une description textuelle en un modèle 3D paramétrique interactif, prêt à être exporté au format **STL** ou en plan 2D **SVG**.

🌐 **Tester l'application en live :** [https://idealj24-max.github.io/MechVision-AI/](https://idealj24-max.github.io/MechVision-AI/)

---

## 🚀 Fonctionnalités Clés

* **📸 Prompt-to-CAD & Vision IA :** Analyse par l'API Gemini (1.5 / 3.6 Flash) pour détecter et calibrer automatiquement les pièces à partir d'une photo ou d'une description textuelle.
* **📐 Modélisation 3D en Temps Réel :** Rendu fluide propulsé par **Three.js** avec contrôles orbitaux et ajustement dynamique des paramètres géométriques (dents, rayons, alésages, épaisseurs).
* **⚖️ Estimation de Masse Industrielle :** Calcul automatique du poids de la pièce selon la matière sélectionnée (Acier C45, Aluminium 6061, Laiton CuZn39, Nylon/PLA).
* **📦 Export STL natif :** Génération instantanée de fichiers 3D 100% compatibles avec les slicers d'impression 3D et les logiciels de CFAO.
* **📐 Plans Techniques 2D :** Export de plans vectoriels au format SVG cotés pour les ateliers.
* **💾 Coffre-Fort Local (Vault) :** Sauvegarde et restauration de vos pièces directement dans le stockage local du navigateur (`localStorage`), fonctionne 100% hors-ligne.

---

## 🛠️ Stack Technique

* **Frontend :** HTML5, Tailwind CSS (Design System Glassmorphic mobile-first).
* **Moteur 3D :** Three.js (r128) + `OrbitControls` + `STLExporter`.
* **Intelligence Artificielle :** Google Gemini API (Vision & Structured JSON Generation).
* **Hébergement :** GitHub Pages (Statique, ultra-rapide, sans serveur lourd).

---

## 🔑 Configuration & Utilisation

1. Rendez-vous sur [Google AI Studio](https://aistudio.google.com/) pour générer votre clé API Gemini gratuite.
2. Ouvrez [MechVision AI](https://idealj24-max.github.io/MechVision-AI/).
3. Cliquez sur l'icône de la clé (**🔑**) dans l'en-tête pour enregistrer votre clé en toute sécurité (stockée uniquement dans votre navigateur).
4. Scannez une pièce ou tapez sa description pour lancer la rétro-ingénierie 3D !

---

## 📄 Licence
Ce projet est open-source. Propulsé par le builder mindset.
