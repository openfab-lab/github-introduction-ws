#Ceci est une introduction à Github
`#Ceci est une introduction à Github`

Je vais ajouter ici plusieurs liens référence:

- https://www.christopheducamp.com/2013/12/15/github-pour-nuls-partie-1/
- https://openclassrooms.com/courses/gerez-vos-codes-source-avec-git
- https://blog.wildcodeschool.fr/pourquoi-utiliser-github-partie-i/
- [14 millions d'inscris en 2016](https://fr.wikipedia.org/wiki/GitHub)
- http://tempsreel.nouvelobs.com/rue89/rue89-explicateur/20150331.RUE8486/qu-est-ce-que-tous-les-techos-du-monde-font-sur-github.html

##dont la synthaxe de mise en forme passe par le langage Markdown
`##dont la synthaxe de mise en forme passe par le langage Markdown`

Les tutoriels pour bien comprendre comment ça marche et le pourquoi, à quoi ça sert.
- [un guide pour bien commencer avec markdown](https://blog.wax-o.com/2014/04/tutoriel-un-guide-pour-bien-commencer-avec-markdown/)
- [OpenClassRoom, Rédigez en Markdown !](https://openclassrooms.com/courses/redigez-en-markdown)

Une ou deux listes Aide-Mémoire 
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [Et une version pdf](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)


Et un extrait rapide des plus courrant (via un exemple de block code):
```
# title

**bold** stuff *italic* [links](http://mors.es)

list:
* coucou
* other item

ordered list:
1. item
2. other item


## subttitle

notes:
> it's a note!

# Team members

Our team:
1. Charley Roelofs
2. Dorian Somers

```

Bolean list, todolist, etc...
- [ ] test1
- [ ] test2
- [ ] test3

--- 

Je rajoute mes notes lors du petit workhop d'introduction organisé par Dorian

# Introduction à Github

à compléter par
http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1/

GIT = framework pour développeur

Utilisation du versionning et de ce framework pour l'adapter à l'utilisation des makers. Le versionning, c'est garder l'historique des évolutions d'un document.
Avec les infos de What, why, who, where?

Les outils d'édition de texte compatible GIT, Latex?
https://fr.wikibooks.org/wiki/LaTeX
https://framakey.org/Pack/PackLatex
les fichiers doc sont fermés et donc non gérable pour le versionning.
Les fichiers qui vont bien et que github va bien gérer:
en 3D, le stl avec un visionneur intégré.
en 2D, les fichiers images jpg, png, ... 
en texte, fichier .txt, .md, .tex, 
Par défaut, on peut imaginer que les types de fichiers propriétaires ne seront pas traité en détail puisque git ne pourra pas les lire pour comparaison, mais on peut quand même les ajouter sur le repository. On compare juste la date et la taille.

à chaque version, un point est créé sur une branche. 
Une branche est un sujet développé, qui n'impacte pas le tronc (Master)
Premier convention: nommer et décrire chaque commit, pas de majuscule, (similaire à slack) 
Utilisation de l'anglais.

Commit: 
lorsqu'on a fait une modification, on "commit" son travail. Les changements sont analysé et disponible à tous pour voir ou questionner les changements.
Un nouveau commit est visible en // avec son précédent pour voir what, why, who, where. 

Merge:
une branche que l'on valide et veut ajouter (merge) au tronc master doit être validé par un pair, jamais par le codeur lui même. 
Pour s'assurer qu'il y a une double lecture, un oeil frais sur ce qui est proposé.

Exemples d'utilisation hors software:
- les lois, très proche de la logique de proposition de loi, validation, et application. 
- l'édition d'un bouquin collaboratif,


Issues?
Lorsqu'on rencontre un bug, soit on le corrige soi-même si on sait, soit on crée une "issue" qui peut servir de feedback ou de signalisation du bug. L'équipe est alors prévenue et quelqu'un peut être assignée à la résolution du bug.
Peut être utilisé pour assigner des taches à des contributeurs/membres.

Les "issues" peuvent être intégrée dans un tableau type Trello/kanban dans l'onglet "projet"


Structure de base? Comment on adapte la structure Github à la gestion de projet openfab?
- Organisation = Openfab, 
- branches = à part la Master, les branches sont des zones tampon de travail que l'on clôt avec merge to master
- projets = 
- milestone = objectif à atteindre
- issues = Tâches

Next step? 
* Installation de GIT chez les utilisateurs, ça permet d'avoir un environnement graphique par dessus GIT, et l'utilisation Offline d'un dossier de travail. Par exemple: Github desktop. 
* organisation des dossiers via concept Flat/nested

Utilisation de l'onglet Wiki pour détailler les protocoles ou le getting started. 


Question/remarque:
* Définir un "protocole" pour nous? un spécial maker parce que sur le net, c'est tjs très orienté développeur.
* pourquoi utiliser GIT et pourquoi faire l'effort d'apprendre le protocole. = Rigueur, nomenclature et convention. C'est comme le code de la route pour pouvoir conduire sur la voie publique et que ça se passe bien.
* comment décider et nommer une branche? =channel slack?
* les codes les plus commun? -> passeport
* la syntaxe de mise en page, les principaux? -> cheatcode passeport
* les règles à suivre? -> passeport
* lien avec https://aisler.net/
ça vient d'un fablab allemand, il met en page les images et permet une recherche de projet DIY sur Github

Quelques liens:
* [Tuto GitHub (exercice)](https://try.github.io/levels/1/challenges/1)
* [Tuto Lewagon (video)](https://www.youtube.com/watch?v=V6Zo68uQPqE)
