# Le jeu de la vie<br>
**Le Jeu de la Vie** est un _automate cellulaire_ , un modèle mathématique inventé par [**John Conway**](https://fr.wikipedia.org/wiki/John_Horton_Conway) en 1970. Ce jeu est particulier car il est considéré comme un _"zéro joueur"_ , c'est-à-dire qu'il n'a pas besoin d'intervention humaine pour fonctionner. Une fois lancé, le jeu évolue tout seul en suivant des règles simples qui déterminent l'apparition ou la disparition de cellules sur une grille.<br>
<br>
## Règles<br>
**Le jeu de la vie** se déroule sur une _grille infinie_ . Chaque cas est considéré comme une _cellule_ . Cette cellule a 2 modes : _vivant ou mort_ . Et après chaque génération, leur mode évolue en fonction des critères suivants

* pour qu'une cellule vivante reste vivante elle doit avoir minimum 2 cellules voisines vivantes<br>
* pour qu'une cellule morte devienne vivante elle doit avoir minimum 3 cellules voisines vivantes<br> 
* Si 1 de c'est 2 condition n'est pas rempli la cellule devient ou reste morte<br>

Et avec des règles aussi simples que ça on arrive à un observateur et créer des **événements aussi fascinants que complexes** .<br> 

<br>



## l'histoire<br>
Créé et inventé dans les années _1870_ par un _professeur de l'université de Cambridge_ [**John Conway**](https://fr.wikipedia.org/wiki/John_Horton_Conway) . Il aura l'idée de ce jeu en cherchant avec un de ses collègues de l'université un moyen pour simuler la vie et l'évolution avec des règles simples afin. Pour réaliser les premières démonstrations à ses élevées il se servira d'un jeu de dame ce qui était moins pratique et moins précis. Par la suite il parlera de ses découvertes dans le journal Scientifique américain dans la même année. On peut facilement faire un lien entre le jeu de la vie et la [**théorie de la soupe**](https://fr.wikipedia.org/wiki/Soupe_primordiale)<br>
<br>

## les différentes structures<br>
Dans **le jeu de la vie** , il existe de nombreux types de structures[^1] différents, mais on va se concentrer sur les plus connus pour avoir les bases du jeu.<br>
On va les séparer en 2 groupes : _ceux qui apparaissent naturellement et ceux qui n'apparaissent pas naturellement_ (soit à l'aide d'un joueur soit lors d'un événement[^2]  )<br>
<br>
1. Les structures naturelles<br>
* _Les structure stable_ : les structure stable est une configuration de cellule vivante qui ne va pas changer lors de la génération suivante c'est a dire qu'elle gardera toujours la même forme<br>
* _Les oscillateurs_ : un oscillateurs est une formation qui reviendra toujours à la même forme après un certain nombre de génération.<br>
* _les vaisseau_ : un vaisseau est une configuration de cellules qui se déplacent à travers la grille en changeant de forme au fil des générations.<br>

![oscillateur](https://github.com/user-attachments/assets/3f97b26f-9198-47a4-8c83-0dc919dc2462)
 



2. Les structures non naturelles<br>
* _jardin d'Eden_ : le jardin d'Éden est une configuration de cellules vivantes qui, lorsqu'elle est placée sur la grille, ne provoque aucune cellule morte à devenir vivante dans la génération suivante. de plus il est
impossible qu'elle apprend seul il faut que le joueur la créer<br>
* _canon_ : c'est une configuration de cellule qui permet de créer des vaisseaux<br>                  
* _puffeur_ : un puffeur est une sorte de vaisseau qui laisse des débris derrière eux<br>



![canon](https://github.com/user-attachments/assets/29ecfdb5-b42c-4fe4-ac48-3e1a865b2fd5)



[^1]: ensemble de cellules vivantes en relation entre elle
[^2]: rencontre entre 2 ou plus de 2 structure qui ce mélange pour en créer une nouvelle



# source<br>
**Wikipédia** :<br>
le jeu de la vie : https://fr.wikipedia.org/wiki/Jeu_de_la_vie<br>
john horton : https://fr.wikipedia.org/wiki/John_Horton_Conway<br>

**YouTube** :<br>
Ego, le jeu de la vie : https://www.youtube.com/watch?v=eMn43As24Bo<br>

## crédit<br>
**créateur** : noroi28<br>
**date** : 09/10/2024<br>
