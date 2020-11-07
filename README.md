# Analyse-Sequences

This README will contain at least a section in English (main)
and another in French.

### Disclaimer

This project is of academic scope and individually mantained. It may not follow best practices or suit your particular purpose of use. Therefore use it at your own risk.

If it were helpful in any way, please let me know! If you would like to contribute to it, hit me up (**PR welcome!**).

## English

Exploration, use and implementation of Python and R tools for DNA sequencing. (Course : Analyse de Séquences)

### Main components

The repository contains both R and Python code. These are the package / virtual environment managers that I use, along with their respective config file. Experimentally  I'm adding support for [Julia](https://julialang.org/).

* Python is managed via [poetry](https://python-poetry.org/).
  
  * pyproject.toml

* R is managed via [renv](https://rstudio.github.io/renv/).
  
  * renv.lock (json format)

I chose these tools because they enable many things which I consider desirable in a project: 

* **Reproducibility**: unlike conda, poetry virtual environments are reproducible).

* **Isolation**: No more cluttering your global Python/R libraries.

### Table of Contents

* Introduction genomes / sequence databases
* Sequence Alignment
* Motif Lookup
* Phylogenetic trees
* Annotation

## Extra notes

If you plan accessing any service provided online by the NIH (like BLAST), you should consider [getting an API key](https://support.nlm.nih.gov/knowledgebase/article/KA-03521/en-us). You can find more info [here]([NCBI Insights : New API Keys for the E-utilities](https://ncbiinsights.ncbi.nlm.nih.gov/2017/11/02/new-api-keys-for-the-e-utilities/)).

## Français

Exploration, emploi et développement d'outils dans les langages de 
programmation Python et R pour l'analyse des séquences. (Cours : M1 
Analyse de Séquences)

### Composants Principaux

Ce dépôt contient du code en R et Python. J'utilise deux 
gestionnaires de paquets / environnements virtuels , un pour chacun. Ce 
sont les suivants, accompagnés de leurs fichiers de configuration 
principaux (C'est-à-dire que si vous avez les gestionnaires installés et
 vous avez les fichiers, vous saurez capables de recréer les 
environnements afin de pouvoir utiliser les codes trouvés dans ce 
dépôt).  

- Python est géré via [poetry](https://python-poetry.org/).
  
  - pyproject.toml  

- R is managed via [renv](https://rstudio.github.io/renv/).
  
  - renv.lock (format json)

Je les ai choisis sur d'autres outils car ils possèdent des 
caractéristiques que je considère désirables dans un projet, notamment:

* **Reproductibilité**: les environnements virtuels de poetry sont reproductibles,  pas comme ceux de conda.

* **Isolation**: Pas de saturation de vos librairies globales (niveau 
  système ou utilisateur). Chaque projet est contenu dans un dossier 
  séparé.
