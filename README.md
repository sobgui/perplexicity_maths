# Simplexcity equation
## Contexte : 
Vous gérez une usine qui produit deux types de produits : A et B. 
Pour fabriquer chaque unité de produit A, il faut 1 heure de travail sur la machine X et 3 heures sur la machine Y. 
Chaque unité de produit B nécessite 2 heures de travail sur la machine X et 1 heure sur la machine Y. 
La machine X est disponible 16 heures par jour, et la machine Y est disponible 24 heures par jour. 
Le profit réalisé par la vente d'une unité de produit A est de 30€, tandis que celui d'une unité de produit B est de 20€.

Objectif : Maximiser le profit quotidien de l'usine.

Votre tâche consiste à déterminer le nombre d'unités de chaque produit (A et B) à produire chaque jour pour maximiser le profit total de l'usine, tout en respectant les contraintes de capacité des machines.

##Solution
Pour résoudre ce problème d'optimisation, nous pouvons formuler un système d'équations basé sur les contraintes de capacité des machines et sur la maximisation du profit.

Soit \( x \) le nombre d'unités de produit A à produire par jour et \( y \) le nombre d'unités de produit B à produire par jour.

Les équations des contraintes sont les suivantes :

1. Contrainte de disponibilité de la machine X : 1x + 2y  <= 16
2. Contrainte de disponibilité de la machine Y : 3x + 1y <= 24 

L'équation de la fonction objectif, représentant le profit total à maximiser, est :

P = 30x + 20y 

Ainsi, le système d'équations est le suivant :
x + 2y  <= 16
3x + y <= 24
P = 30x + 20y

Maintenant, nous pouvons résoudre ce système d'équations pour déterminer les valeurs optimales de x et y.

### Démarches mathématiques
- Trouver les points d'intersection des deux inégalités.
- Calculer la valeur du profit total pour chaque point d'intersection.
- Sélectionner le point d'intersection qui maximise le profit total.
