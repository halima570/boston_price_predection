# Boston Price Prediction

##  Description

Ce projet utilise le dataset Boston Housing pour prédire les prix des logements à Boston à l’aide de modèles de machine learning. L’objectif est de construire un modèle capable d’estimer la valeur médiane des maisons en se basant sur des caractéristiques telles que le taux de criminalité, le nombre de pièces, les distances aux centres d’emploi, etc.

---

##  Fonctionnalités principales

- Analyse exploratoire des données (EDA)  
- Prétraitement : gestion des variables manquantes, transformation si nécessaire  
- Sélection des caractéristiques les plus pertinentes  
- Construction de modèles de régression (ex. : régression linéaire, SVR…)  
- Évaluation des performances via métriques (MAE, MSE, R², etc.)  
- Visualisations : graphiques de corrélation, performances modèle, comparaisons

---

##  Technologies utilisées

- **Langage** : Python  
- **Environnement** : Jupyter Notebook (`.ipynb`)  
- **Bibliothèques** :
  - `numpy`, `pandas` pour la manipulation des données  
  - `matplotlib`, `seaborn` pour les visualisations  
  - `scikit-learn` pour les modèles et métriques

---

##  Installation & exécution

1. **Cloner le dépôt**

    ```bash
    git clone https://github.com/halima570/boston_price_predection.git
    cd boston_price_predection
    ```

2. **Installer les dépendances**

    Si un `requirements.txt` est présent :

    ```bash
    pip install -r requirements.txt
    ```

    Sinon installe manuellement :

    ```bash
    pip install numpy pandas scikit-learn matplotlib seaborn notebook
    ```

3. **Lancer le notebook**

    ```bash
    jupyter notebook
    ```

4. **Ouvrir le fichier principal**

    Ouvre le fichier `boston_house.ipynb` pour retrouver l’implémentation, l’analyse et les résultats.

---

##  Utilisation

- Lance le notebook pour exécuter les cellules étape par étape : chargement des données, exploration, prétraitement, entraînement du modèle, évaluation et visualisations.
- Tu peux modifier les modèles utilisés ou tester d’autres algorithmes pour améliorer les prédictions.
- Compare les performances de différents modèles via les métriques calculées.


