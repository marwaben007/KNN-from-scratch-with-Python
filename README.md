# KNN-from-scratch-with-Python
KNN from scratch with Python

KNN: La recherche des k plus proches voisins consiste à trouver dans un ensemble de A de n points, k points de A les plus proches d’un point x.


À l’aide des bibliothèques prédéfinies de python: 
Scikit learn
Numpy 
Pandas
Matplotlib
Python datasets
On va essayer d’implémenter une méthode optimisée pour trouver les k proches voisins et la classe correspondante pour chaque point.


Livrable 1: on utilise 
Liste contenant les premiers k points
Pour chaque autre point dans la liste A on calcul la distance avec la donnée x
Si on trouve un point qui a une distance inférieure aux autres distances des premiers k points, on le remplace avec le point qui a la distance maximale.



Livrable 2
On utilise les dictionnaires
La clé est le couple (distance(a[i], x), i). On ajoute l’indice i pour éviter la redondance pour les points qui ont la même distance. 
 La valeur est le point a[i]. 
Trier le dictionnaire et prendre les premiers k points
Et on ccompare entre les 2 resultats du livrable 1 et2.



Livrable 3
Programmation de 3 fonctions 
Distance pour calculer la distance entre 2 points
KNN pour trouver la classe de x
Accuracy pour calculer la justesse



Conclusion: 
IRIS DATA
la justesse:  KKN projet est la meilleure    
temps d’exécution: la méthode scikit learn est la meilleure



Cancer DATA
la justesse: les deux méthodes ont la meme justesse (pour k=24 la méthode projet est la meilleure)
temps d’exécution: la méthode scikit learn est la meilleure


 Lwf_pairs DATA
la justesse: la méthode scikit learn est la meilleure
Temps d’exécution: la méthode scikit learn est la meilleure
