# **Projet Python 2A**

**Tony Lauze - Fanny Daubet**

*Ce projet est réalisé dans le cadre du cours de Python pour la data-science de Lino Galiana, pour l'année 2023-2024.*

Le but de ce projet est de **modéliser le prix de l'immobilier en région parisienne** et, plus précisément, des appartements dans Paris intra-muros.

La base de donnée principale qui sera utilisée, est le **fichier Demandes de Valeurs Foncières (DVF)**, produit par la direction générale des finances publiques, qui recense les transactions immobilières intervenues au cours des cinq dernières années en France, à partir des actes notariés.

Comme toutes les ventes de ce fichier sont géolocalisées, l'enrichissement principal qui sera apporté à la base de données sera l'ajout, pour chaque appartement, de la **distance minimale à certains lieux d'intérêt parisiens** (stations de métro, espaces verts, lieux historiques, etc.).

Le **rapport final** se trouve dans le notebook `RAPPORT_FIN.ipynb`. A plusieurs étapes du projet, des fonctions définies dans les fichiers `Enrichissement.py` et `Visualisation.py`, mais aussi dans les dossiers `1.0) Nettoyage` et `1.2) Données concat` sont utilisées, afin de faciliter la lecture.

La fonction et le contenu de chacun des dossiers présents dans ce dépôt, seront précisés dans le rapport au fur et à mesure du projet.
