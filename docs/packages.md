# Packages

## Nommage standard des packages 


### En générale 

Il existe des normes courantes pour nommer les packages dans différents langages de programmation :

* **Minuscules:** Les noms de packages s'écrivent généralement en minuscules. Cela permet d'éviter les conflits avec les noms de classes ou d'interfaces, qui peuvent être en majuscules.
* **Clarté:** Le nom doit refléter clairement le but du package. Les développeurs doivent pouvoir facilement comprendre les fonctionnalités fournies par le package.
* **Concision:** Visez un nom concis et descriptif, mais pas trop long.
* **Séparation:** Pour les noms composés, certains langages utilisent CamelCase (par exemple, gestionnaireRéseau) tandis que d'autres séparent les mots par des points ou des traits de soulignement (par exemple, réseau.gestionnaire ou gestionnaire_reseau).

Voici quelques détails supplémentaires pour des langages spécifiques :

* **Java:** Les noms de packages commencent souvent par un nom de domaine inversé (par exemple, com.exemple.monpackage) pour établir la propriété et éviter les conflits.
* **Go:** Bien qu'il n'y ait pas d'exigence stricte, l'utilisation de minuscules et de traits de soulignement pour la séparation est une pratique courante.

### En php 

En PHP, il n'existe pas de standard unique et obligatoire pour les noms de packages. Cependant, il existe des conventions et des recommandations fortes à suivre pour la lisibilité et la cohérence :

* **Minuscules avec tirets:** C'est la convention la plus courante pour les packages Composer (le gestionnaire de paquets principal de PHP). Les noms de packages sont en minuscules, les mots étant séparés par des tirets (par exemple, `mon-vendeur/paquet-utile`).
* **Descriptif:** Le nom doit clairement communiquer les fonctionnalités fournies par le package.
* **Concis:** Visez un nom facile à comprendre, mais pas trop long.
