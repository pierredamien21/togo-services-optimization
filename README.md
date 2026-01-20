# Optimisation des Services Publics au Togo 
### Analyse de la Performance Opérationnelle - Exercice 2023

##  Présentation du Projet
Ce projet propose une analyse basée sur la donnée pour optimiser la délivrance des documents officiels (CNI, Passeports, Actes) au Togo. En exploitant un jeu de données de **52 837 demandes** traitées en 2023, ce travail identifie les leviers d'amélioration pour réduire les délais et augmenter l'équité territoriale.

**Principaux enjeux identifiés :**
* **Délai moyen de traitement :** 22,7 jours (Cible nationale : 15 jours).
* **Taux de rejet :** 34,0 % (Goulot d'étranglement majeur).
* **Digitalisation :** 50,8 % (Transition amorcée mais à perfectionner).

---

##  Organisation du Dépôt (Arborescence)

Voici le guide des fichiers présents dans ce dépôt pour comprendre la structure du projet :

### 1.  Traitement & Analyse (Code Python)
* **`/scripts/nettoyage_preparation_donnes.ipynb** : Script d'automatisation du nettoyage des données (normalisation des noms de communes, gestion des doublons et formatage temporel).
* **`/notebooks/EDA.ipynb`** : Analyse exploratoire détaillée incluant les calculs des 7 KPI et les visualisations de corrélation (Python, Pandas, Plotly).

### 2.  Application Dashboard
* **`/app/readme`** : texte dans lequel se trouve le lien du dasboard 
* **`/data/master_data_cleaned.csv`** : Jeu de données final consolidé utilisé par le dashboard.

### 3.  Livrables & Documentation
* **`/docs/rapport.pdf`** : Rapport final rédigé en **LaTeX** détaillant les 7 KPI, les limites méthodologiques et les recommandations.
* **`/docs/presentation.pptx`** : Support PowerPoint  résumant le diagnostic et la feuille de route.

### . Les KPI
* **`/KPI/KPI.xlsx`** : presente les kpi utliser pour le projet.

---
