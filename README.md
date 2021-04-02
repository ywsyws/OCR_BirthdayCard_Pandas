# OCR_BirthdayCard_Pandas

#### Contexte

Vous avez une idée de start-up ! Vous souhaitez vendre des cartes de vœux pour les anniversaires... Ca parait simple, mais attention, il y a un twist ! Vous voulez faire un type de cartes de vœux pour le jour de la semaine de naissance du destinataire. Vous aurez ainsi 7 types de cartes différents.

Vous aimeriez prévoir la quantité de cartes à créer. Malheureusement, vous ne savez pas quelle quantité commander pour chaque jour. Mais vous avez accès aux données de naissance aux États-Unis dans ce [fichier](https://raw.githubusercontent.com/jakevdp/data-CDCbirths/master/births.csv) (eh oui, vous partez directement à l'international !)

#### Consigne

1. Vous allez livrer un graphique avec trois courbes qui représentent le nombre de naissances pour chaque jour de la semaine pour les décennies 1960, 1970 et 1980.
2. Cette tâche implique un peu de nettoyage de données, et un peu d’algèbre linéaire. Vous aurez certainement besoin d'un peu de traitement avec la fonction ```to_datetime``` pour transformer les données en objets ```datetime``` (et un peu de connaissance en Python pour comprendre ce que c'est). Pour cet exercice, faites attention à ces points :
    1. Nettoyage de la colonne births.
    2. Conversion des colonnes day, month et year en datatime.
    3. Conversion en jour de semaine.
    4. L'agrégation doit être faite grâce à librairies Pandas.