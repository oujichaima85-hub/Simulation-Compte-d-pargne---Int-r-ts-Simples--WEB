# 🏦 Simulateur d'Épargne Tunisien (TND)

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Tech](https://img.shields.io/badge/Tech-HTML5%20%7C%20CSS3%20%7C%20JS-orange)

Calculateur d'intérêts simples et composés interactif conçu pour modéliser des comptes d'épargne en **Dinars Tunisiens (TND)**.

## ✨ Fonctionnalités

* **Interface Interactive** : Ajustement des paramètres via des sliders dynamiques.
* **Calculs en Temps Réel** : Mise à jour instantanée des résultats sans rechargement.
* **Visualisation Graphique** : Graphiques d'évolution du capital via **Chart.js**.
* **Analyse Comparative** : Comparaison directe entre intérêts simples et intérêts composés.
* **Tableau de Bord** : Tableau d'amortissement détaillé période par période.
* **Design Responsive** : Optimisé pour une utilisation sur mobile, tablette et desktop.

## 🚀 Installation & Utilisation

Le projet est "Zero-Configuration". Aucun serveur n'est requis.

1.  **Téléchargez** ou **Clonez** le dépôt :
    ```bash
    git clone [https://github.com/votre-nom-utilisateur/simulateur-interets-tnd.git](https://github.com/votre-nom-utilisateur/simulateur-interets-tnd.git)
    ```
2.  **Ouvrez** le fichier `projet_finance.html` dans votre navigateur Web préféré.

## 📊 Paramètres Supportés

| Paramètre | Plage de réglage |
| :--- | :--- |
| **Capital Initial** | 100 TND à 1 000 000 TND |
| **Taux d'Intérêt** | 0.5% à 15% |
| **Durée** | 1 à 30 ans |
| **Fréquence** | Annuel, Trimestriel, Mensuel |

## 🛠️ Stack Technique

* **Frontend** : HTML5, CSS3 (Flexbox/Grid)
* **Logique** : JavaScript (ES6+)
* **Visualisation** : Chart.js

## 📐 Modèles de Calcul

Le moteur de calcul utilise les formules financières standards :
- **Intérêts Simples** : $V_f = C \times (1 + r \times t)$
- **Intérêts Composés** : $V_f = C \times (1 + \frac{r}{n})^{n \times t}$

---
*Développé pour l'éducation financière et la simulation de placements en Tunisie.*
