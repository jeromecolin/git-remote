###1-Projet client : récap du rdv client, création rétroplanning, répartitions des tâches, démarrage du travail de codage et de création des pages.

###2-les live codings : 

    - Symfony CRUD :  un CRUD est un système de manipulation des données de la base : ça signifie Create, Read, Update, Delete(Créer, Lire, Mettre à jour, Supprimer).
Autrement dit, on va faire une interface pour gérer nos données. Cela peut entre autres servir à créer une interface d'administration pour votre site.
Préparation du terrain
Récapitulatif
Avant de commencer, récapitulons la structure de notre projet. Jusqu'à maintenant je vous ai simplement indiqué où placer quelques fichiers.
Nous utiliserons cette structure :

~/config/
----global.php
----schema.yml
~/html/
~/lib/
----models/
--------Article.php
--------ArticleTable.php
--------User.php
--------UserTable.php
--------generated/
------------BaseArticle.php
------------BaseUser.php
~/web/
----index.php

Si vous avez suivi le tutoriel en entier, vous ne devriez rien avoir à faire. Dans le cas contraire, je vous laisse vous reporter aux chapitres précédents pour connaître le contenu de ces fichiers.
Comme je vous l'ai dit, nous allons grandement simplifier le modèle MVC : nous aurons un contrôleur frontal (~/web/index.php) qui se chargera aussi d'inclure la page HTML.
liens videos livecoding : 
        -Symfony CRUD (sans formulaire) : https://www.loom.com/share/68edb9fd83624f23a966935f3e4f40e9
        -Symfony CRUD (avec formulaire et make:crud) : https://www.loom.com/share/a39c5a5d5a1a46d5be640704e21a1133

###3-Intervention Rugbycentric :
Guillaume Bourda est venu nous faire un exercice qui est utilisé pour les recrutements chez Google, Facebook, etc. 
La problèmatique était créer une application pour gérer les places d'un parking. 
Pour se faire il a joué le rôle du client et nous a fait interagir par groupe de deux afin que nous trouvions la solution idoine pour la gestion des données.
Ce fut une intervention très instructive et enrichissante tant au point de vue personnel qu'au point de vue collectif.


