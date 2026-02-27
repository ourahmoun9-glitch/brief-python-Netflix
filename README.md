Analyse du Catalogue Netflix
📌 Contexte du projet

Vous travaillez en tant que Data Analyst pour une plateforme de streaming.
La direction souhaite mieux comprendre le catalogue Netflix afin d’identifier :

📈 Les tendances et performances des contenus

🎬 La répartition des films vs séries

🌍 Les genres et pays de production dominants

🔞 La classification d’âge des contenus

⏳ L’évolution du catalogue dans le temps

Ce projet couvre l’ensemble de la chaîne analytique :
exploration → nettoyage → préparation → visualisation → insights métier

L’objectif final est de produire un rapport analytique complet, puis de préparer les données pour un futur dashboard interactif (Power BI).

🎯 Objectifs du projet

Explorer et analyser le dataset Netflix avec Python et Pandas.

Produire des visualisations pertinentes avec Matplotlib et Seaborn.

Répondre aux questions métier liées aux contenus.

Identifier les tendances principales du catalogue.

Préparer les données pour un futur dashboard interactif.

🛠️ Technologies utilisées

🐍 Python

📊 Pandas

📈 Seaborn

📉 Matplotlib

📓 Jupyter Notebook

📂 Structure du projet
Netflix-Analysis/
│
├── netflix_analysis.ipynb
├── netflix_titles.csv
└── README.md
🔎 1️⃣ Exploration des données (EDA)

Objectif : comprendre le dataset avant toute transformation.

Actions réalisées :

Vérification des types et structure (info(), describe())

Identification des valeurs manquantes

Analyse des distributions (films vs séries, ratings, pays, genres)

Détection des doublons

🧹 2️⃣ Préparation et nettoyage des données

Objectif : préparer le dataset pour l’analyse finale.

Transformations effectuées :

Gestion des valeurs manquantes

Suppression des doublons

Conversion de date_added en format datetime

Création de la variable dérivée year_added

Transformation des colonnes multi-valeurs (country, listed_in) avec split() et explode()

Harmonisation des formats (dates, durées, types)

📊 3️⃣ Visualisations et analyse métier

Les analyses suivantes ont été réalisées :

📌 Répartition des contenus par classification d’âge (rating)

🎬 Proportion de films vs séries

📈 Nombre de contenus ajoutés chaque année

🔄 Évolution du catalogue : films vs séries par année

📺 Nombre de séries entre 2011 et 2021

🌍 Nombre de productions par pays

🌎 Productions par pays et par classification d’âge (heatmap)

🎭 Analyse des genres (listed_in)

🔎 Identification des genres les plus fréquents

Types de visualisations utilisés :

Bar charts

Pie charts

Line charts

Count plots

Heatmaps

📈 Insights métier
🔥 Tendances principales

Les Dramas dominent le catalogue Netflix.

Les Films représentent la majorité du contenu.

Les productions sont concentrées principalement aux États-Unis, suivis de l’Inde et du Royaume-Uni.

Le rating TV-MA est le plus fréquent (contenu adulte).

Forte croissance du catalogue entre 2016 et 2019.

📊 Observations stratégiques

Netflix investit fortement dans les contenus dramatiques.

Le catalogue est majoritairement orienté vers un public mature.

Opportunité de diversification géographique et de classification d’âge.

Le format série représente un potentiel d’expansion futur.

🚀 Lancer le projet

Cloner le repository

git clone <repo_url>

Installer les dépendances

pip install pandas seaborn matplotlib

Ouvrir le notebook

jupyter notebook netflix_analysis.ipynb
