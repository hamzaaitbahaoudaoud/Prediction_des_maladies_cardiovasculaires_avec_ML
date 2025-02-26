# Classification des Maladies Cardio-vasculaires avec des Algorithmes de Machine Learning

Ce projet explore l'utilisation d'algorithmes d'apprentissage supervisé pour prédire la présence ou l'absence d'une maladie cardio-vasculaire à partir d'un ensemble de données médicales. Il couvre tout le pipeline de machine learning, depuis le prétraitement des données jusqu'à la comparaison des modèles pour sélectionner le meilleur.
Notez bien que ce projet est fait au sein du cours de l'apprentissage automatique pour la première année de cycle des ingénieurs en génie logiciel, afin de mettre en évidence les compétences aqcuises au cours des séances. Des erreurs peuvent être existants.
Le jeu de données 'heart_data.csv' existe sur Kaggle sous le lien: https://www.kaggle.com/datasets/thedevastator/exploring-risk-factors-for-cardiovascular-diseas/data

## Contenu du Projet
* Prétraitement des données :
Nettoyage des données, gestion des valeurs manquantes et normalisation des variables pour garantir des entrées cohérentes dans les modèles.

* Visualisation des données :
Analyse exploratoire des données (EDA) pour comprendre la distribution des variables et les corrélations importantes à travers des graphiques tels que les histogrammes, les heatmaps et les scatter plots.

* Modélisation :
Entraînement et évaluation de plusieurs algorithmes de machine learning, notamment :

    * Régression Logistique
    * K-Nearest Neighbors (KNN)
    * Arbre de Décision
    * Forêt Aléatoire
* Évaluation et comparaison des modèles :
Utilisation des courbes ROC et des courbes Précision-Rappel, ainsi que des scores d'évaluation tels que l'accuracy, le F1-score, la précision et le rappel pour comparer les modèles et sélectionner le meilleur.

* Résultat final :
Forêt Aléatoire a été identifié comme le meilleur modèle grâce à ses performances supérieures sur les courbes ROC et Précision-Rappel.

## Technologies Utilisées
* Python (pandas, numpy, matplotlib, seaborn, scikit-learn)
* Jupyter Notebook
## Objectif du Projet
Ce projet vise à démontrer comment utiliser des algorithmes de classification dans un cadre supervisé pour résoudre un problème médical critique, avec une mise en œuvre rigoureuse et des analyses détaillées.
