﻿# email-scraper
 <h1>Un scraper d’emails</h1>
 <p>Le scraping est une technique qui consiste à extraire des données spécifiques depuis des sites web lambda. Notre scraper d’emails vous servira à récolter toutes les adresses emails apparaissant dans le code source d’une page web donnée. Le code du scraper vous est fourni (vous devrez toutefois bien le comprendre), votre travail se situera essentiellement dans ce que nous ferons des emails trouvés.</p>
 <h4>Travail à faire</h4>
 <ol>
  <li>Vous allez ensuite créer une base de données composée d’une table Emails contenant un unique champ « email » de type varchar(128) et qui sera aussi la clé primaire de la     table.</li>
  <li>A l’aide du framework Medoo (dont le fichier vous est fourni) vous allez créer une page web myscraper.php dont la fonction sera d’ajouter en base de données toutes           adresses emails trouvées à une url donnée. Si vous n’avez jamais utilisé Medoo jusqu’à présent, consultez la dernière section de cet exercice.</li>
  <li>Ajoutez désormais un formulaire à votre page web dans lequel vous pourrez saisir une url dans un input. En soumettant ce formulaire, votre scraper ira extraire les           adresses emails trouvées à l’url donnée et les ajoute en base de données. Une fois le travail terminé, il recharge le formulaire.</li>
  <li>Enfin, après chaque scraping, vous afficherez le nombre d’adresses emails trouvées ainsi que la liste de ces emails dans votre page dans un joli tableau, sous le formulaire.</li>
  <li>Pour terminer proprement l’exercice, passez un petit coup de CSS sur votre code afin de le rendre plus présentable.</li>
</ol>
<h1>Bonus</h1>
<p>Essayez d’optimiser au mieux le requêtage en essayant d’envoyer un maximum d’informations en un minimum de requêtes.</p>

