# Projet d'analyse des stratégies de trading algorithmique - tradingStrategiesAnalysis
Ce projet consiste à analyser l'impact des stratégies de trading algorithmique sur la liquidité des marchés financiers en utilisant la théorie des jeux appliquée à la finance.
## Fonctionnement du projet
Le projet est divisé en deux fichiers :
* `tradingStrategies.py` : contient les stratégies de trading algorithmique.
* `tradingStrategiesAnalysis.py` : contient les fonctions d'initialisation des traders, de calcul des commissions et de sélection des stratégies les plus viables au cours du temps.

Les données sont récupérées via l'API `yfinance` et sont mises à jour très rapidement de sorte à ce qu'un court laps de temps soit suffisant pour faire des simulations.

Le projet utilise également du multithreading pour accélérer les calculs.

## Dépendances du projet

Les dépendances du projet sont listées dans le fichier `requirements.txt`.

## Installation

- Clonez le projet depuis GitHub : `git clone https://github.com/votre_nom/projet-trading.git`
- Installez les dépendances : `pip install -r requirements.txt`

## Utilisation

- Ouvrez le fichier `tradingEnvironment.py` et modifiez les paramètres si nécessaire.
- Exécutez le fichier `tradingEnvironment.py` : python tradingEnvironment.py