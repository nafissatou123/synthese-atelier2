<h3>ACTIVITÉ PRATIQUE N2 : Développement d'un micro service</h3><BR>
<h4>Créer un micro service qui permet des gérer des comptes bancaires.</h4><br>

<h3>QUESTION 1</h3>
<p>Créer un projet Spring Boot avec les dépendances Web, Spring Data JPA, H2, Lombok</p>
<img src="Captures/capture1.jpg" alt=""><br><br>

<h3>QUESTION 2</h3>
<p>Créer l'entité JPA Compte</p>
<img src="Captures/capture2.jpg" alt=""><br><br>

<h3>QUESTION 3</h3>
<p>Créer l'interface CompteRepository basée sur Spring Data</p>
<img src="Captures/capture3.jpg" alt=""><br><br>

<h3>QUESTION 4</h3>
<p>Tester la couche DAO</p>
<ul><li>Execution :<img src="Captures/capture4.jpg" alt=""></li>
<li> Base de données : BankAccount <img src="Captures/capture5.jpg" alt=""></li>
</ul><br>

<h3>QUESTION 5</h3>
<p>Créer le Web service Restfull qui permet de gérer des comptes</p>
<img src="Captures/capture6.jpg" alt=""><br><br>

<h3>QUESTION 6</h3>
<p>Tester le web micro-service en utilisant un client REST : Postman</p>
<ul>
<li>Methode Get : Récupération de la liste des comptes.
<img src="Captures/capture7.1.jpg" alt=""></li>
<li>Methode Post : Ajout d'un nouveau comptes.
<img src="Captures/capture7.2.jpg" alt=""></li>
<li>Methode Put : Modification d'un compte grace a son identifiant.
<img src="Captures/capture7.3.jpg" alt=""></li>
</ul><br>

<h3>QUESTION 7</h3>
<p>Générer et tester la documentation Swagger des API Rest du Web service</p>
<ul>
<li>Accueil de la documentation : <img src="Captures/capture12.jpg" alt=""></li>
<li>Affichage de la documentation de l'api rest : <img src="Captures/capture12.1.jpg" alt=""></li>
<li>Affichage de la liste des comptes : <img src="Captures/capture12.get.jpg" alt=""></li>
<li>Affichage du compte en fonction de l'id : <img src="Captures/capture12getId1.jpg" alt=""><img src="Captures/capture12getId2.jpg" alt=""></li>
<li>Ajout d'un compte via la documentation swagger : <img src="Captures/capture12.post.jpg" alt=""><img src="Captures/capture12post1.jpg" alt=""></li>
</ul><br>

<h3>QUESTION 8</h3>
<p>Exposer une API Restful en utilisant Spring Data Rest en exploitant des projections</p>
<ul><li>Service restfull 1 : Spring data rest : <img src="Captures/capture8.jpg" alt=""></li>
<li>Service restfull 2 : Data rest controller : <img src="Captures/capture9.jpg" alt=""></li>
<li>Service restfull 1 : Pagination : <img src="Captures/capture9.1.jpg" alt=""></li>
<li>Service restfull 1 : Rechercher par type:CURRENT_ACCOUNT <img src="Captures/capture10.1.jpg" alt=""></li>
<li>Service restfull 1 : Rechercher par type:SAVING_ACCOUNT <img src="Captures/capture10.jpg" alt=""></li>
<li>Service restfull 1 : Affichage par projection  <img src="Captures/capture11.jpg" alt=""></li></ul><br>

<h3>QUESTION 9</h3>
<p>Créer les DTOs et Mappers</p>
<img src="Captures/capture13.jpg" alt="">
<p>Test d'ajout d'un compte :</p><img src="Captures/capture12.post.jpg" alt=""><img src="Captures/capture12post1.jpg" alt=""><br><br>


<h3>QUESTION 10</h3>
<p>Créer la couche Service (métier) et du micro service</p>
<img src="Captures/capture14.jpg" alt="">

<h3>QUESTION 11</h3>
<p>Créer un Web service GraphQL pour ce Micro-service</p>
<ul>
<li> Consulyer la liste des comptes avec graphQL <img src="Captures/capture15.jpg" alt=""> </li><br>
<li>Récupérer les informations d'un compte grace a l'identifiant <img src="Captures/capture16.jpg" alt=""></li><br>
<li>Personnaliser le message d'erreur lorsqu'un compte n'exsite pas <img src="Captures/capture17.jpg" alt=""></li><br>
<li>Ajouter un nouveau compte via de variables prédéfinies <img src="Captures/capture18.jpg" alt=""></li><br>
<li>Modifier les informations d'un compte grace a l'identifiant <img src="Captures/capture19.jpg" alt=""></li><br>
<li>Supprimer un compte grace a l'identifiant <img src="Captures/capture20.jpg" alt=""></li><br>
<li>Consulter la liste des comptes avec leurs clients correspondants <img src="Captures/capture21.jpg" alt=""></li><br>
<li>Consulter la liste des clients et leurs comptes respectifs (id , nom, comptes) <img src="Captures/capture22.jpg" alt=""></li><br>
</ul>

<h3>FIN</h3>




