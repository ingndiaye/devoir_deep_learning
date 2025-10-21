# TP – CNN "From Scratch" vs Transfer Learning (Cats vs Dogs)

## Objectif
Ce projet vise à comparer deux approches d’apprentissage profond sur un même jeu de données **Cats vs Dogs** :
1. Un **modèle CNN entraîné from scratch**.
2. Un **modèle utilisant le transfert d’apprentissage** (basé sur ResNet18 pré-entraîné).

L’objectif est de démontrer l’impact du **transfert learning** sur la rapidité de convergence, la précision et la robustesse du modèle.

---

## Contenu du projet

- **`ABDOURAHMANE_NDIAYE_TP.ipynb`** → Notebook principal contenant les deux expériences.
- **`requirements.txt`** → Liste des bibliothèques nécessaires.
- **Jeu de données** : dossier contenant les images de **chats** et **chiens**, organisé ainsi :
  ```
  data/
  ├── train/
  │   ├── cats/
  │   └── dogs/
  └── val/
      ├── cats/
      └── dogs/
  ```

---

## Installation

1. **Cloner le projet ou copier le notebook :**
   ```bash
   git https://github.com/ingndiaye/devoir_deep_learning.git 
   ```
 
2. **Installer les dépendances :**
   ```bash
   pip install -r requirements.txt
   ```

---

##  Exécution

1. Ouvrir le notebook :
   ```bash
   jupyter notebook ABDOURAHMANE_NDIAYE_TP.ipynb
   ```

2. Exécuter les cellules dans l’ordre :
   - Chargement et transformation des données
   - Définition du modèle **from scratch**
   - Entraînement et évaluation
   - Définition du modèle **en transfert learning (ResNet18)**
   - Comparaison des performances

---

##  Auteur
**Abdourahmane Ndiaye**  
TP Deep Learning – CNN Cats vs Dogs  
DIT
