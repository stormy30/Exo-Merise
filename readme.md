![Merise](http://sqlpro.developpez.com/cours/bddexemple/images/mcdHotel.gif)

# Exos-Merise

## Exercice n°1
* Etant donné les fiches suivantes :
  - FILMS renseignés avec titre, date de sortie, durée
  - ACTEURS renseignés avec nom, prénom, nationalité, âge
  Réalisez les étapes de la conception citées ci-dessous,
   en utilisant la méthode Merise :
   
               Première étape : repérage des entités
               FILMS et ACTEURS
               Deuxième étape : repérage des relations et écrire les règles de gestion métiers.
               un film est joué de 0 à plusieurs acteurs
               un acteur joue dans 0 à plusieurs films 
               role avec atributs principal secondaire figuration
               
               Troisième étape : identification des entités et écrire le dictionnaire des données.
               dictionnaire des données :VOIR PDF
               Quatrième étape : définir les dépendances fonctionnelles.
               Cinquième étape : établir le Modèle Conceptuel des Données (MCD).
               
## Exercice n°2
* En prenant l'exercice 1, on ajoute les fiches PRODUCTEURS renseignés avec nom, raison sociale.
  Réalisez les étapes de la cvonception citées ci-dessus, en utilisant la méthode Merise,
  sachant que :
  
              un producteur finance plusieurs films et qu'un film peut être financé par plusieurs producteurs.
              pour chaque film on connaît le montant de financement d'un producteur qui y participe.
  REPONSE PDF :MCD Q2
## Exercice n°3
* une compagnie d'aviation propose des vols(auxquels elle attribue un numéro, un type d'avion, un matricule de
  pilote, un nombre de passager) au départ de certaines villes(connues par leur nom, la dénomination de l'aéroport et
  le pays) et à destination d'autres villes, les départs ont certaines caractéristiques(heure d'enregistrement, heure de
  départ, hall et porte de départ, ...) les arrivées en ont de différentes (heure d'arrivée, hall de récupération des
  bagages, ...)
  Réalisez les étapes de la conception citées ci-dessus.
   *1 repérages des entités : villes et vols
   *2 relations : un  vol est en partance et a destination d'une ville 
                  une ville est la destinnation et le point de départ de plusieurs vols
                  
                  
                  