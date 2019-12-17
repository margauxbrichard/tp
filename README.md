<h1>TP Architecture</h1>
<p>Voici le fichier PHP permettant de gérer la pagination d'une liste de commentaire.</p>
<p>Veuillez cloner mon dépot et déposer sur le votre (en ligne) une version corrigée du tp.<br>
Vous prendrez en charge les extrémités (première page et dernière page) dans l'affichage des numéros de pages.</p>

J'ai créé une base données sur MySQL afin d'afficher des commentaires dans mon formulaire et avoir une pagination, ensuite j'ai modifié le fichier commentaires.php : 
- Modification de la ligne 13 en enlevant le MDP "root".
- Modification de la ligne 67 si i < 0 alors ne rien afficher et sinon afficher le nombre de pages avec la bonne pagination allant de 1 à 5. 