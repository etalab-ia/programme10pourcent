---
title: "Faciliter la production de publications statistiques ou de reporting territorial"
summary: Faciliter la production de publications statistiques ou de reporting territorial, par la mise à disposition d'outils facilitant la préparation de données
responsible: Juliette ENGELAERE-LEFEBVRE (DREAL Pays de la Loire)
date: 2022-05-18T13:00:00+01:00
images: 
- /img/image-ocr.png
---
 
##### Les objectifs
Faciliter la production de statistiques territoriales en développant ou en contribuant à des solutions open source.
Plusieurs packages R ont été développés pour faciliter la gestion des évolutions du COG (Code Officiel Géographique) dans le traitement des statistiques territoriales.
En effet, des communes fusionnent, se séparent, changent de département, ou de communautés de communes chaque année et gérer correctement ces évolutions est un préalable à la production d'indicateurs territoriaux fiables.
Les packages COGiter, COGugaison et Cartelette ont été développés pour faciliter ses travaux, ils doivent êtres minutieusement maintenus chaque année pour intégrer les dernières évolutions du COG et pourraient être amélioré (processus de mise à jour annuel, tickets en cours, recours au API de contours administratifs comme https://geo.api.gouv.fr/decoupage-administratif...) voir comporter des briques communes.

 
##### Exemples de cas d'usage
Réaliser une carte en rond proportionnel d'évolution de la population par EPCI entre 2018 et 2013.
Produire un tableau d'indicateurs, par exemple pour une région données, indiquer le nombre de logement sociaux par zone, à l'échelle des principaux EPCI, départements, région, France de province, France entière (exemple https://rdes_dreal.gitlab.io/propre.rpls/articles/b-ch1.html#creer-tableau-1-1)
Autres exemples d'usages : 
https://maeltheuliere.github.io/COGiter/articles/cogiter.html
https://dreal-datalab.gitlab.io/mapfactory/articles/creer_carte.html
https://antuki.github.io/COGugaison/articles/COGugaison.html
##### Domaines techniques
* Langage R
* Développement de package avec usethis, pkgdown et devtools
 
 
##### Les profils recherchés
* Développeur
* Data analyst
* Statisticien
 
 
##### Ressources utiles
* COGugaison : https://github.com/antuki/COGugaison
* Cartelette : https://github.com/antuki/CARTElette
* COGiter : https://github.com/MaelTheuliere/COGiter
* Mapfactory : https://gitlab.com/dreal-datalab/mapfactory
