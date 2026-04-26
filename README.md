# Analyse et prédiction de la gravité des accidents de la route
## Contexte du projet
Ce projet s’inscrit dans le cadre d’un projet tutoré en data science. Il a pour objectif d’analyser les déterminants de la gravité des accidents de la circulation à partir de données accidentologiques, en mobilisant des méthodes de traitement de données, d’économétrie et de Machine Learning / Deep Learning.
La gravité des accidents routiers constitue un enjeu majeur de sécurité publique. Comprendre les facteurs associés aux accidents graves permet d’améliorer les politiques de prévention et les dispositifs de sécurité routière.

## Objectifs
Les objectifs principaux du projet sont :

Explorer et comprendre la structure des données d’accidents de la route
Identifier les facteurs expliquant la gravité des accidents
Tester et comparer différentes approches :

économétriques (paramétriques) pour l’interprétation,
Machine Learning / Deep Learning (non paramétriques) pour la prédiction


Mettre en évidence les limites et les complémentarités entre ces approches


## Structure du projet
Le projet est organisé en trois notebooks principaux, conformément à la méthodologie vue en cours :
### Structure du projet
.
├── EDA_Econometrie
│   └── Analyse exploratoire et econometrie.ipynb
├── Non_parametrique
│   └── Machine Learning (Approches non paramétriques).ipynb
├──  Traitement_de_données
│   └──  Traitement_de_donnees.ipynb
├──  data_bases
│   └── (données utilisées dans le projet)
├──  .gitignore
└──  README.md

## Notebook 1 – Traitement de données
Ce premier notebook est consacré à la préparation et à la compréhension des données :

chargement et nettoyage des données,
gestion des valeurs manquantes,
création et transformation de variables (âge, classes, indicateurs contextuels),
analyses exploratoires :

univariées,
bivariées,
multivariées,


détection des valeurs aberrantes,
étude de l’équilibre des classes,
analyses exploratoires avancées (tests du χ², ACP, ACM).

### Objectif : préparer des données propres et cohérentes pour la modélisation.

#### Notebook 2 – Économétrie (approches paramétriques)
Ce notebook vise à expliquer économiquement la gravité des accidents à l’aide de modèles paramétriques :

régression linéaire (modèle de référence),
régression logistique binaire,
modèles Logit et Probit (robustesse),
modèle Logit multinomial (modélisation complète de la gravité).

L’accent est mis sur :

l’interprétation économique des coefficients,
la significativité statistique,
la validation des hypothèses,
les limites des modèles paramétriques.

### Objectif : comprendre et interpréter les déterminants de la gravité.

#### Notebook 3 – Machine Learning et Deep Learning
Ce notebook est dédié à une approche orientée prédiction, reposant sur des méthodes non paramétriques :

préparation des données pour le ML,
gestion du déséquilibre des classes,
modèles de Machine Learning :

régression logistique (baseline prédictive),
Random Forest,
autres modèles supervisés,


introduction de modèles de Deep Learning (réseaux de neurones),
comparaison des performances (accuracy, F1-score, matrices de confusion),
comparaison avec les modèles économétriques.

### Objectif : améliorer la performance prédictive et comparer les approches explicatives et prédictives.

#### Méthodologie générale
Le projet suit une démarche progressive et cohérente :

Exploration et préparation des données
Analyse explicative par l’économétrie
Analyse prédictive par le Machine Learning / Deep Learning
Comparaison des résultats et discussion

Cette approche permet de montrer la complémentarité entre économétrie et Machine Learning.

Remarques importantes

Les fichiers techniques (ex. .DS_Store, .ipynb_checkpoints) sont ignorés via le fichier .gitignore.
Les résultats présentés dépendent du jeu de données utilisé et de sa qualité.
Les modèles ML visent la performance prédictive, tandis que les modèles économétriques privilégient l’interprétation.


##### Conclusion
Ce projet met en évidence que la gravité des accidents de la route résulte d’une combinaison complexe de facteurs liés à l’environnement, aux infrastructures et aux caractéristiques des usagers.
L’association de méthodes économétriques et de techniques de Machine Learning permet d’obtenir une analyse à la fois interprétable et performante, répondant aux objectifs du projet.