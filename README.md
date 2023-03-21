# Exploration de la librairie openpyxl
Automatisation d'un traitement Excel avec Openpyxl



L'objectif du traitement est de fournir un exemple d'automatisation qui pourrait être réalisé avec les données du brfss.

Plus précisément, le brfss (le système de surveillance des facteurs de risque comportemental en français) est le premier système national d'enquêtes téléphoniques liées à la santé qui collectent des données d'état sur les résidents des États-Unis concernant leurs comportements à risque liés à la santé, leurs problèmes de santé chroniques et l'utilisation des services de prévention.


Ce dernier étant réalisé chaque année, il pourrait être intéressant de réaliser un fichier excel annuel comprenant les informations globales ayant été collectées. 
Etant donné le nombre très important de colonnes du dataset initial (330 environ par année) et le caractère illustratif de l'exercice, je n'ai retenu que 11 colonnes pour la réalisation de ce rapport reprenant des informations sur la socio-démographie, le tabagisme et la santé mentale des répondants. Pour les mêmes raisons, je n'ai collecté que les jeux de données des années 2018 et 2019.


Enfin, la passation du questionnaire étant auprès de 400 000 individus chaque année, un échantillon de 50 000 personnes par année sera créé afin de limiter les temps de chargement. 


Le fichier ipynb du traitement est consultable sur ce repo.
Source des données : https://www.cdc.gov/brfss/annual_data/annual_data.htm
