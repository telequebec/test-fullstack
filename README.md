# Instructions
Vous devez fournir une solution Visual Studio contenant un projet de type 'site web' qui pourra être lancé en debug et qui répondra à la problématique ci-dessous...

# But
=> Afficher une liste de personnages de Star Wars dans une page web

# Contraintes
=> Back-end : 
Vous ne pouvez utiliser que .Net Core en langage C#.

=> Front-end: 
Vous devez écrire le programme en JavaScript natif dans une de ses dernières versions (pas de jQuery ni autre framework!).

À développer et fournir :
=> Back-end : 
Un end point de Web API mettant à disposition la liste des personnages Star Wars issus du fichier json fourni dans le projet (ce fichier devra être inclu et lu dans le projet en tant que source de données).
Un test unitaire avec la librairie de votre choix.

=> Front end : 
Une vue MVC avec un minimum de HTML/CSS (titre, tableau) permettant un affichage clair de la liste des personnages Star Wars. 
Le contenu du tableau doit donc être servi en Javascript par appel à votre Web API. 
Vous devez afficher les caractéristiques suivantes pour chacun des personnages : name, height, mass et le nombre de films dans lequel le personnage apparaît. 
De plus, vous devez laisser le soin à l’utilisateur de modifier l’ordre dans lequel les personnages apparaissent : par ordre alphabétique (name), par taille (height), par la masse (mass) ou par le nombre de films.

# Remarque
Il est important qu'un simple F5 sur le projet fourni permette de faire fonctionner cette solution.
