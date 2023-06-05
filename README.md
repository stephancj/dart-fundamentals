# Concepts fondamentaux de Dart

## Exercice 1: Types de variables
Déclarez les variables suivantes en utilisant les types appropriés :

Un entier appelé "age" initialisé à 25.
Un nombre décimal appelé "pi" initialisé à 3.14159.
Une chaîne de caractères appelée "nom" initialisée à "Alice".
Un booléen appelé "estVrai" initialisé à true.


## Exercice 2: Conditions
Écrivez un programme qui demande à l'utilisateur d'entrer un nombre. Si le nombre est pair, affichez "Le nombre est pair", sinon affichez "Le nombre est impair".

## Exercice 3: Boucle
Écrivez un programme qui affiche tous les nombres de 1 à 100 à l'aide d'une boucle while.

## Exercice 4: Boucle et conditions
Écrivez un programme qui affiche tous les nombres pairs de 1 à 50. Utilisez une boucle for et une condition pour vérifier si le nombre est pair.

## Exercice 5: Table de multiplication
Écrivez un programme qui demande à l'utilisateur d'entrer un nombre et affiche sa table de multiplication de 1 à 10.

## Exercice 6: List
Créez une liste contenant 5 fruits de votre choix. Parcourez la liste et affichez chaque élément.
Créez une liste contenant 5 légumes de votre choix. Parcourez la liste et affichez chaque élément.
Créez une nouvelle liste contenant les éléments de la liste des fruits et des légumes.

## Exercice 7: Manipulation de List
Créez une liste "list1" contenant les nombres de 1 à 5. Ajoutez le nombre 6 à la liste. Supprimez le nombre 3 de la liste. Parcourez la liste et affichez chaque élément.

## Exercice 8: Set
Créez un ensemble contenant les nombres suivants : 1, 2, 3, 4, 5, 3, 2. Affichez les éléments uniques de l'ensemble.

## Exercice 9: Manipulation de Set
Créez un ensemble vide. Ajoutez les nombres de 1 à 5 à l'ensemble. Ajoutez à nouveau le nombre 3 à l'ensemble. Supprimez le nombre 2 de l'ensemble. Affichez les éléments de l'ensemble.

## Exercice 10: Map
Créez un dictionnaire  (Map) représentant les prix de 10 fruits de votre choix :  Affichez les fruits et leurs prix.

## Exercice 11: Manipulation de Map
Créez un dictionnaire vide pour stocker les prénoms et les âges. Ajoutez les paires clé-valeur suivantes à la carte : "Alice" - 25, "Bob" - 30, "Charlie" - 35. Affichez les clés de la carte. Affichez les valeurs de la carte.


# NULL SAFETY:

## Exercice 1: Vérification de la nullité
Écrivez une fonction appelée "afficherLongueur" qui prend une chaîne de caractères en paramètre et affiche sa longueur. Si la chaîne est null, affichez "Chaîne vide". Testez votre fonction en lui passant différentes valeurs, y compris une valeur null.

## Exercice 2: Opérateur de coalescence nulle (Null aware operator) "??"
Écrivez une fonction appelée "calculerAge" qui prend un paramètre "anneeDeNaissance" de type int? (pouvant être null) et renvoie l'âge calculé. Si l'année de naissance est null, renvoyez la valeur par défaut de 18. Utilisez l'opérateur de coalescence nulle "??" pour simplifier votre code.

## Exercice 3: Conversion de valeurs nullables
Écrivez une fonction appelée "convertirEnEntier" qui prend une chaîne de caractères en paramètre et renvoie la valeur entière correspondante. Si la chaîne est null ou ne peut pas être convertie en entier, renvoyez 0. Utilisez la méthode int.tryParse pour effectuer la conversion en toute sécurité.




