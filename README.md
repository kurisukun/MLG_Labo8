# MLG - Labo8: THE BURMAN TRAVELING SALESMAN PROBLEM



> **Auteur:** Chris Barros Henriques
>
> **Date:** 18.06.21
>
> HEIG-VD



## 6.1

The objective of this exercise is to solve the TSP problem for a set of 14 cities in Burma, officially the Republic of the Union of Myanmar. The following vectors give the GPS position of each city.

<div style="page-break-after: always; break-after: page;"></div>

Le problème qui nous est donné ici est celui du problème du voyageur de commerce. En se basant sur une liste de villes et leurs distances respectives, on souhaite déterminer quelle est la route qui permet de passer une seule fois dans chaque ville, minimisant le chemin parcouru et permettant à la fin de revenir à notre point de départ. Plus précisément, il nous est donné un ensemble de 14 paires de coordonnées GPS de villes du Myanmar et de déterminer quel est le chemin optimal résolvant le problème du voyageur de commerce.

C'est un problème NP-complet mais son importance est grande dans le domaine des sciences informatiques et bien d'autres.



La solution proposée utilise un algorithme génétique. L'idée est de représenter les chemins que l'on effectue par une liste ordonnée de nombre de 1 à 14, chacun représentant l'indice d'une coordonnée GPS dans les tableaux fournis. Par exemple, `1 2 3 4 5 6 7 8 9 10 11 12 13 14` est un chemin possible. L'algorithme va ensuite calculer la distance totale parcourue et la retenir. Il va ensuite faire muter le chromosome (le chemin trouvé) afin de toujours minimiser la distance (par exemple le chemin `1 2 3 4 13 14 5 6 7 8 9 10 11 12` peut être une meilleure solution).



## 6.2





## 6.3





<div style="page-break-after: always; break-after: page;"></div>



## 6.4



## 6.5







<div style="page-break-after: always; break-after: page;"></div>



## 6.6 Plots



<div style="page-break-after: always; break-after: page;"></div>



## 6.7 Conclusion







