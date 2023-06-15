[[Java Learning Book]]
========================

Réference du cours 
------------------

```
  https://openclassrooms.com/fr/courses/6173501-apprenez-a-programmer-en-java
```


[[Jour 1 2023-06-13]]
------------
Les variables:
Une variable un conteneur servant à stocker une données qui va être utilisée par un programme informatique.
En java pour utiliser une variable il faut d'abord la déclarer comme suite:

```
 type nom = valeur;
```

Exemple :
```
$ int price = 10;
```

Les types primitives en Java sont : Boolean, Byte, Short, Int,Long, Float et Double

Nb: Par convention les variables sont nommées en CamelCase :une phrase composée de plusieurs mots sans espaces ni ponctuation. Le premier mot est écrit en minuscules et tous les autres mots commencent par une majuscule

Exemple :

```
$  byte productReference = 25;
```

Les constantes sont des variables qui ne changent pas.Par convention les constantes sont nommées en majuscule et précédé par le mot clé ``final``. Si le nom est un nom composé il faut separer chaque partie par un underscore

Exemple :

```
$ String  USER_ROLE = "admin";
```

[[Jour 2 2023-06-15]]
---------------------

Les fonctions
Une founction est un bloc de code  avec un nom qui exécute un service. Lorsqu'elle est definie dans une classe, elle s'appelle une méthode
En java la fonction main est le point d'entrée de notre programmme. C'est elle qui est appelé lorsque le programme est lancé. Elle prend en paramètre une un tableau d'arguments

Nb: Deux étapes sont nécessaire à l'exécution d'un programme java: La compilation et l'interprètation

Compilation:
Intervient en amont pour prendre le code du développeur et le transformer en byteCode 

Interprètation:
Traduit le byteCode en instructions pour exécuter le programme

Les modules 
Une module est ensemble de fichiers sources associés à un nom,comme un framwork. Un framework est un ensemble de fonctionnalités regroupées par contexte particulier.Ceci permet d'accélérer le processus de développement en donnant des conseils sur la façon d'écrire le code

Un package regroupe des classes liées entre elles. C'est un peu comme un vrai paquet rempli de petites choses, sauf que ces choses sont des classes



