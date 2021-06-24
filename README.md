# Birthdate
Calculer l'age de naissance à partir d'un age donné 
Dans cet exercice, nous utilisons la classe datetime du module datetime pour faire des calculs de date.

On commence tout d'abord par récupérer l'année actuelle avec :

    annee_actuelle = datetime.today().year

Puis le mois actuel de la même façon :

    mois_actuel = datetime.today().month

On fait ensuite une soustraction entre l'année actuelle et l'âge de la personne contenu dans la variable 'age'.

On fait une dernière petite vérification dans un opérateur ternaire pour vérifier si le mois de naissance de la personne en question est plus grand que le mois actuel ou non. Si oui, on retire une année supplémentaire à l'année de naissance, si non, on ne retire rien de plus (else 0).
