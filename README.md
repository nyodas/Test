# Zara - Maps #

## Besoins , Objectifs ##
L'objectif de la pages est de fournir une visualisation des performances des commerciaux et leur magasin.
Ainsi que de fournir un apperçu du trajet prevu par ces commerciaux.

Les Managers , Responsables ont egalement besoin d'un visualisation des performances des _zones (commerciaux)_ sous leurs coupes.

*   **Visualisation des performances.**
    * Des Magasins
    * Des Commerciaux
    * Des G-Store

*   **Planification des Visites et informations relative**
    * Afficher la derniere Visite.
    * Planifié la visite.
    * Voir le Quota de Visite

* Afficher une carte reprenant le trajet des magasins planifié

## Fonctionnalité Commerciaux
_KPI_ *(Key Performance Indicator)*

__Echelle couleur : Performance__

1. __Rouge__ : *Mauvais*
2. __Jaune__ : *Moyen*
3. __Vert__ : *Bon*

### Totaux
![PKI Totaux](/Total.jpg "Total.jpg")

    Un Bandeau avec des KPI concernant l'ensemble des magasins de la zone.
    0. Un bandeau qui représente l'etat de la zone (Repris par une iconne representant le status)
    1. Le budget
    2. Le Chiffre d'affaire.
    3. Le Running Point.
    4. Le Budget a Realisé et à realisé par jour pour atteindre les objectifs.
    5. 1 Graphe en Donnut representant le %realisé
    6. 1 Graphe en Donnut representant le %realisé pour l'ensemble des Commerciaux de la section.
    7. La position de l'avancement de sa zone comparer au autres commerciaux

### Magasin
![PKI Magasin ](/PKIMAG.jpg "PKIMAG.jpg")

    Chaque Magasin present dans la liste du commercial affiche plusieurs __KPI__.
    0. L"etat du Magasin : un ruban de couleur indiquant la performance du Magasin
    1. Le Poids du Magasin
    2. La Dernière visite Planifié(Colorisé en fonction du delta entre Maintenant et cette date)
    3. Le Quota et le Delta entre la Quota de visite et le nombre de visite planifié dans le mois.
    4. Le Budget Attribué au magasin (*Chiffre a effectué*)
    5. Le Chiffre D'affaire Realisé et sont % par rapport au Budget
    6. Le Running Point : Represente le %de CA realisé par rapport a l'avancement du mois
    7. Le Budget à realisé : Represente le Budget Restant sur le reste du mois.
       Le Montant a realisé chaque jour avant la fin du mois pour remplir les objectif.

### Diagramme , Graphique en Barre
![Graphique Barre Verticale](/Graph.jpg "Graph.jpg")

Un diagramme dynamique est présent en haut de la page.
il contient 80% des informations contenu dans les performance magasins.
Les KPI de budget , CA et leur % de realisation sont present.
La couleur de fond du diagramme represente le statut de la zone du commercial.

## Planning &amp; Map
![Planning Global](/planning.jpg "planning.jpg")

Chaque Magasin a l'option d'être plannifié pour la semaine S+2.
Il est egalement possible de visualisé le planning de la semaine en cour et celle S+1.
Les modification du Planning engendre une mise a jour de la couverture.
Cette Couverture est affiché sur le planning recapitulatif de la semaine.

![Map Global](/map.jpg "map.jpg")

Un trajet peut être genere pour fournir une idée de l'efficacité de la planification.

## Fonctionnalité Manager
Il y a des similarité entre le mode Manager et le Mode Commercial.
- Diagramme
- Totaux
- Planning
- Magasin (Visible grace au bouton +)


### Graphique ,Diagramme
Le Diagramme Vertical affiche les nom des commerciaux a la place des magasins.
    Les Chiffres sont basé sur la performance de leur zone.

Un click sur la barre d'un commercial permet d'afficher les % realisé des magasins lié à celui-ci.

### Filtre et Totaux.
![Filtre Manager](/sectionFilter.jpg "filtreSection.jpg")
>Les Filtre permettent de changer la Section Affichée ainsi que le planning visible.

![Totaux Manager](/orderTotal.jpg "ordreTotal.jpg")

Des boutons permettent d'ordoné la liste des commerciaux affichés.
Les PKI de la section sont egalement affichés.

### Planning.
#### Validation.
![planning Manager](/planningManager.jpg "planningManager.jpg")

Il est possible de valider les prochainne visite des Commerciaux via les bouton positioné au dessus du planning.

#### Historique
![Historique planning](/planningHisto.jpg "planningHisto.jpg")

Il est possible de voir une historique grâce au bouton etant representé par une icon de Calendrier. :calendar:

Les dates du planning sont selectionnable grace au bouton situé en bas de la page.

Les Fleche Indique la Semaine Suivante ou Precedente.

Le bouton du milieu ouvre un Calendrier pour selectionner une semaine particulière.

#### Performance
![Performance Manager](/perfManager.jpg "perfManager.jpg")

Le bouton Tachymètre vous envoie sur bilan rapide des commerciaux de la zone.
Il sont classé par ordre de performance.

#### Dernière Visite
![visite Manager](/visiteManager.jpg "visiteManager.jpg")

Cette page est accecible par le bouton calculette dans le Total de la zone (Santé de l'equipe).

Des Filtres et options pour ordonnée la liste de magasins est présente sur la gauche.

    0. Ordonée par Numéro de Magasin
    1. Ordonée par Criticité du nombre de Visite
    2. Ordonée par Nombre de Visite
    3. Filtrer par texte.
    4. Filtrer par date de Debut et de Fin.

La page affiche le nombre de visite.
Les visites individuelle, et la section des commerciaux qui ont visité.






