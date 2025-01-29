# Data Pipeline pour la Prédiction et la Visualisation

Ce projet met en œuvre une pipeline de données pour extraire, transformer et visualiser des données météorologiques en utilisant des outils modernes d'analyse de données.

## Description

Le projet suit un flux ETL (Extract, Transform, Load) où les étapes sont les suivantes :
1. **Extraction** des données météorologiques via l'API OpenWeather.
2. **Transformation** des données avec Python et Jupyter pour appliquer des algorithmes de prédiction (régression, classification) et de clustering.
3. **Chargement** des données dans une base de données **Oracle**.
4. **Visualisation** des résultats dans **Power BI**.

### Outils utilisés
- **OpenWeather API** : Pour l'extraction des données météorologiques.
- **Python** : Pour la transformation et l'application des algorithmes d'analyse de données.
- **Jupyter Notebook** : Pour le développement et l'exécution du code Python.
- **Scikit-learn** : Pour les modèles de machine learning (régression, classification, clustering).
- **Oracle Database** : Pour stocker et gérer les données.
- **Power BI** : Pour la visualisation des résultats.

## Prérequis

Avant de commencer, assurez-vous d'avoir installé les outils et dépendances suivants :
- Python 3.x
- Jupyter Notebook
- Bibliothèques Python : `requests`, `pandas`, `scikit-learn`, `cx_Oracle`
- Oracle Database (ou un accès à une instance Oracle)
- Power BI
