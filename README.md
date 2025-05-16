<p align="center">
   <img src="https://www.asc-csa.gc.ca/images/recherche/tiles/radarsat_1_hr.jpgÈ alt="Radarsat" height=300> 
   <br> Crédit d'image | Image credit: <a href=https://www.asc-csa.gc.ca/images/recherche/tiles>ASC-CSA</a>
</p>


<p align="center">
    <a href="#stars">
        <img alt="Étoiles sur GitHub | GitHub Repo stars" src="https://img.shields.io/github/stars/asc-csa/EO-Visualization-and-Search-Tutorial">
    </a>
    <a href="#watchers">
        <img alt="Spectateurs sur Github | GitHub watchers" src="https://img.shields.io/github/watchers/asc-csa/EO-Visualization-and-Search-Tutorial">
    </a>
    <a href="https://github.com/asc-csa/EO-Visualization-and-Search-Tutorial/commits/main">
        <img alt="Dernier commit sur GitHub | GitHub last commit" src="https://img.shields.io/github/last-commit/asc-csa/EO-Visualization-and-Search-Tutorial">
    </a>
    <a href="https://github.com/asc-csa/EO-Visualization-and-Search-Tutorial/graphs/contributors">
        <img alt="Contributeurs sur GitHub | GitHub contributors" src="https://img.shields.io/github/contributors/asc-csa/EO-Visualization-and-Search-Tutorial">
    </a>
    <a href="https://twitter.com/intent/follow?screen_name=csa_asc">
        <img alt="Suivre sur Twitter | Twitter Follow" src="https://img.shields.io/twitter/follow/csa_asc?style=social">
    </a>
</p>

<h2 align="center">
  <a href="#titre-du-projet">Français</a> |
  <a href="#project-title">English (follows)</a>
</h2>

<!-- ============ FRANÇAIS ============ 
An engaging title for the project (required)-->
<a id="titre-du-projet"></a>
# Visualisation-et-la-Recherche-d'Images-Tutoriel

<!-- A short summary phrase for the project (required)-->
> **Description brève :**
> Ce tutoriel initie les utilisateurs à l’exploration des vastes données RADARSAT-1 et RCM en utilisant l’API REST du SGDOT pour rechercher et visualiser des images satellites sur une carte interactive.

---

## À propos

RADARSAT-1 a fourni au Canada et au monde entier une plateforme avancée de radar à synthèse d'ouverture (SAR) capable d'acquérir des images de la Terre.<br>

La Mission Constellation RADARSAT (MCR) était la prochaine génération du programme RADARSAT, offrant une qualité, une quantité et une couverture améliorées de 90 % de la surface de la Terre. Ceci a été accompli en offrant trois satellites uniformément espacés sur la même altitude orbitale de 600 km.<br>

La recherche et la distribution de ces images sont assurées par le système de gestion des données d'observation de la Terre (SGDOT) géré par Ressources naturelles Canada (RNCan).<br>

Les données disponibles par l'entremise du SGDOT sont vastes, car on s'attend à ce que le MCR prenne environ 250 000 images par année et que RADARSAT-1 capture plus de 710 000 images accessibles au public au cours de sa durée de vie.<br>

Par conséquent, ce tutoriel vise à faire découvrir aux lecteurs ces vastes données en utilisant le SGDOT par le moyen de l'API REST qui l'accompagne pour rechercher et afficher l'imagerie satellitaire de RARDARSAT-1 et de RCM sur une carte interactive.

## Démarrage rapide

1. 📦 **Cloner le dépôt**
   ```bash
   git clone https://github.com/asc-csa/EO-Visualization-and-Search-Tutorial.git
   cd EO-Visualization-and-Search-Tutorial
   ```
2. 🐍 **Créer un environnement**
   ```bash
   # Avec virtualenv
   python -m venv env
   source env/bin/activate

   # Ou avec conda
   conda create -n rad_env python=3.11
   conda activate rad_env
   ```
3. 📥 **Installer les dépendances**
   ```bash
   pip install -r requirements.txt
   ```
4. 🚀 **Lancer le tutoriel**
   ```bash
   jupyter notebook Visualisation et la Recherche d'Images OT Tutoriel - FR.ipynb.ipynb
   ```
> **Remarque :** Si les graphiques ou cartes ne s’affichent pas, redémarrez Jupyter Notebook ou ajoutez `%matplotlib inline` dans la première cellule.

## Licence

Ce projet est  sous une licence MIT modifiée – voir le fichier [LICENSE](https://github.com/asc-csa/EO-Visualization-and-Search-Tutorial/blob/main/LICENSE.txt) pour plus de détails.

---

<h2 align="center">
  <a href="#project-title">English </a> |
  <a href="#titre-du-projet">Français (précède)</a>
</h2>

<!-- ============ English ============ 
An engaging title for the project (required)-->
<a id="project-title"></a>
# EO-Visualization-and-Search-Tutorial

<!-- A short summary phrase for the project (required)-->
> **Brief description:**
> This tutorial introduces users to exploring the extensive RADARSAT-1 and RCM data using the EODMS REST API to search and display satellite imagery on an interactive map.

## About

RADARSAT-1 provided Canada and the world with an advanced synthetic aperture radar (SAR) platform capable of acquiring images of the Earth.<br>

The RADARSAT Constellation Mission (RCM) was the next generation of the RADARSAT Program, offering improved quality, quantity and coverage of 90% of Earth’s surface. This was accomplished by offering three satellites that were evenly spaced on the same orbital altitude of 600km.<br>

The search and distribution of these images is provided by the Earth Observation Data Management System (EODMS) managed by Natural Resources Canada (NRCan).<br>

The available data through EODMS is vast, with RCM expected to take approximately 250,000 images per year, and RADARSAT-1 capturing over 710,000 publicly available images over its lifetime.<br>

Therefore, this tutorial will look to engage readers with this vast data through the use of EODMS through its accompanying REST API to search and display satellite imagery from RARDARSAT-1 and RCM on an interactive map.


## Quick Start

1. 📦 **Clone the repo**
   ```bash
   git clone https://github.com/asc-csa/EO-Visualization-and-Search-Tutorial.git
   cd EO-Visualization-and-Search-Tutorial
   ```
2. 🐍 **Create environment**
   ```bash
   # Using virtualenv
   python -m venv env
   source env/bin/activate

   # Or using conda
   conda create -n rad_env python=3.11
   conda activate rad_env
   ```
3. 📥 **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. 🚀 **Run the tutorial**
   ```bash
   jupyter notebook EO Visualization and Search Tutorial - EN.ipynb
   ```
> **Note:** If plots or maps do not display, restart Jupyter Notebook or run `%matplotlib inline` in the first cell.

## License

This project is licensed under a modified MIT license - see the [LICENSE](https://github.com/asc-csa/EO-Visualization-and-Search-Tutorial/blob/main/LICENSE.txt) file for details.
