<!DOCTYPE html>
<html lang="fr">
	<head>
		<meta charset="utf-8">
		<meta http-equiv="x-ua-compatible" content="ie=edge">
<!-- ELEMENT IMPORTANT POUR QUE MA PAGE SOIT RESPONSIVE -->
		<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
        <title>RESERVIA</title>

		<link rel="preconnect" href="https://fonts.gstatic.com">
		<link href="https://fonts.googleapis.com/css2?family=Raleway:wght@400;700&display=swap" rel="stylesheet">	
        <link rel="stylesheet" type="text/css" href="css/styles.css">
        <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css" integrity="sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p" crossorigin="anonymous"/>
	</head>

	<body>




<main>

        <header>

			<a href="#"><h1><img class="logo" src="img/logo/Reservia.svg" alt="logo reservia"></h1></a>

            <nav>
				
				<ul>
					
					<li>
						<a href="#hebergements">Hébergements</a></li>
					<li>
						<a href="#activites">Activités</a></li>
					<li>
						<a href="#">S'inscrire</a></li>

				</ul>

			</nav>

        </header>

		<section>

			<div class="titre2"><h2>Trouvez votre hébergement pour des vacances de rêve</h2></div>
			<div class="zone_texte"><p>En plein centre ville ou en pleine nature</p></div>

			<!-- zone de saisie + bouton de recherche -->

			<form method="post" action="#">
				<div class="iconemap"><i class="fas fa-map-marker-alt"></i></div>
				<input type="text" id="zonedesaisie" value="Marseille,France"/>
				<button class="bouton"><span>Rechercher</span><i class="fas fa-search"></i></button>
			</form>

		</section>

    
<!-- FILTRES -->

	<section class="enveloppe_filtres">

		<div class="filtre_text">Filtres</div>

		<div class="fusion">

			<div class="icone"><i class="fas fa-money-bill-wave"></i></div>
			<div class="filtre">&Eacute;conomique</div>

		</div>


		<div class="fusion">

			<div class="icone"><i class="fas fa-child"></i></div>
			<div class="filtre">Familial</div>

		</div>


		<div class="fusion">
			
			<div class="icone"><i class="fas fa-heart"></i></div>
			<div class="filtre">Romantique</div>

		</div>

		<div class="fusion">
			
			<div class="icone"><i class="fas fa-dog"></i></div>
			<div class="filtre">Animaux autorisés</div>

		</div>

	</section>


		<div class="info">

			<div class= "iconecercle"><i class="fas fa-info-circle"></i></div>
			<p class="infor">Plus de 500 logements sont disponibles dans cette ville</p>

		</div>
		


<!-- BLOCS CARD -->

<section class="container" id="hebergements">

	<div class="bloc_h">
		
			<h2>Hébergements à Marseille</h2>

		<div class="cards_h">
			
				<div class="card_h">
					<a href="">
					<img src="img/hebergements/4_small/marcus-loke-WQJvWU_HZFo-unsplash.jpg" alt="visuel activite marseille">

					<div class="description_h"> 
						<h3>Auberge de Cannebière</h3>
						<p>Nuit à partir de <b>25€</b></p>
						<div class="star4">
							<i class="fas fa-star"></i>
							<i class="fas fa-star"></i>
							<i class="fas fa-star"></i>
							<i class="fas fa-star"></i>
							<i class="fas fa-star"></i>
						</div>
					</div>
					</a>
				</div>
			

			
				<div class="card_h">
					<a href="">
					<img src="img/hebergements/4_small/fred-kleber-gTbaxaVLvsg-unsplash.jpg" alt="visuel activite marseille">

					<div class="description_h"> 
							<h3>Hôtel du port</h3>
							<p>Nuit à partir de <b>52€</b></p>
						<div class="star5">
							<i class="fas fa-star"></i>
							<i class="fas fa-star"></i>
							<i class="fas fa-star"></i>
							<i class="fas fa-star"></i>
							<i class="fas fa-star"></i>
						</div>
					</div>
				</a>	
				</div>
			


			<div class="card_h">
				<a href="">
				<img src="img/hebergements/4_small/reisetopia-B8WIgxA_PFU-unsplash.jpg" alt="visuel activite marseille">

				<div class="description_h"> 
						<h3>Hôtel Les Mouettes</h3>
						<p>Nuit à partir de <b>76€</b></p>
					<div class="star4">
						<i class="fas fa-star"></i>
						<i class="fas fa-star"></i>
						<i class="fas fa-star"></i>
						<i class="fas fa-star"></i>
						<i class="fas fa-star"></i>
					</div>
				</div>
			</a>		
			</div>



			<div class="card_h">
				<a href="">
				<img src="img/hebergements/3_medium/annie-spratt-Eg1qcIitAuA-unsplash.jpg" alt="visuel activite marseille">

				<div class="description_h"> 
						<h3>Hôtel de la mer</h3>
						<p>Nuit à partir de <b>46€</b></p>
					<div class="star3">
						<i class="fas fa-star"></i>
						<i class="fas fa-star"></i>
						<i class="fas fa-star"></i>
						<i class="fas fa-star"></i>
						<i class="fas fa-star"></i>
					</div>
				</div>
			</a>		
			</div>



			<div class="card_h">
				<a href="">
				<img src="img/hebergements/4_small/nicate-lee-kT-ZyaiwBe0-unsplash.jpg" alt="visuel activite marseille">

				<div class="description_h"> 
						<h3>Auberge Le Panier</h3>
						<p>Nuit à partir de <b>23€</b></p>
					<div class="star4">
						<i class="fas fa-star"></i>
						<i class="fas fa-star"></i>
						<i class="fas fa-star"></i>
						<i class="fas fa-star"></i>
						<i class="fas fa-star"></i>
					</div>
				</div>
			</a>		
			</div>


			<div class="card_h">
				<a href="">
				<img src="img/hebergements/4_small/febrian-zakaria-M6S1WvfW68A-unsplash.jpg" alt="visuel activite marseille">

				<div class="description_h"> 
						<h3>Hôtel chez Amina</h3>
						<p>Nuit à partir de <b>96€</b></p>
					<div class="star5">
						<i class="fas fa-star"></i>
						<i class="fas fa-star"></i>
						<i class="fas fa-star"></i>
						<i class="fas fa-star"></i>
						<i class="fas fa-star"></i>
					</div>
				</div>
			</a>		
			</div> 

		

		</div>

		<p><b>Afficher plus</b></p>
	</div>



	<div class="bloc_v">
		<div class="titre_icone">
			<h2>Les plus populaires</h2>
			<i class="fas fa-chart-line"></i>
		</div>

		
			
	
				<div class="cards_v">
					<a href="">		
					<div class="card_v">
		
						<img src="img/hebergements/4_small/emile-guillemot-Bj_rcSC5XfE-unsplash.jpg" alt="visuel activite marseille">

						<div class="description_v">
								<h3>Hôtel Le soleil du matin</h3>
								<p>Nuit à partir de <b>128€</b></p>
							<div class="star5">
								<i class="fas fa-star"></i>
								<i class="fas fa-star"></i>
								<i class="fas fa-star"></i>
								<i class="fas fa-star"></i>
								<i class="fas fa-star"></i>
							</div>
						</div>
				</div>
			</a>

			
				<a href="">
					<div class="card_v">
				
						<img src="img/hebergements/4_small/aw-creative-VGs8z60yT2c-unsplash.jpg" alt="visuel activite marseille">
	
						<div class="description_v">
								<h3>Au coeur de l'eau Chambres d'hôtes</h3>
								<p>Nuit à partir de <b>71€</b></p>
							<div class="star4">
								<i class="fas fa-star"></i>
								<i class="fas fa-star"></i>
								<i class="fas fa-star"></i>
								<i class="fas fa-star"></i>
								<i class="fas fa-star"></i>
							</div>
						</div>	
					</div>
				</a>


						<a href="">
							<div class="card_v">
								<img src="img/hebergements/4_small/febrian-zakaria-sjvU0THccQA-unsplash.jpg" alt="visuel activite marseille">
			
								<div class="description_v">
									<h3>Hôtel Tout bleu et blanc</h3>
									<p>Nuit à partir de <b>68€</b></p>
									<div class="star4">
										<i class="fas fa-star"></i>
										<i class="fas fa-star"></i>
										<i class="fas fa-star"></i>
										<i class="fas fa-star"></i>
										<i class="fas fa-star"></i>
									</div>
								</div>
							</div>
						</a>

			</div>

	</div>
</section>


	<!-- DERNIER BLOC -->


	<h2 class="marseille" id="activites">Activités à Marseille</h2>

<section class="blocs">

	<div class="bloc3">
		
		<a href="">

			<div class="cardz">
				<img class="cardi" src="img/activites/4_small/reno-laithienne-QUgJhdY5Fyk-unsplash.jpg" alt="visuel activite marseille">
				<p><b>Vieux Port</b></p>
			</div>

		</a>

	</div>



	<div class="bloc3">
		
		<a href="">
			<div class="cardz">

				<img class="cardi2" src="img/activites/4_small/paul-hermann-QFTrLdQIRhI-unsplash.jpg" alt="visuel activite marseille">
				<p class="text2"><b>Fort de Pomègues</b></p>

			</div>
		</a> 


		<a href="">
			<div class="cardz">

				<img class="cardi3" src="img/activites/4_small/kevin-hikari-rV_Qd1l-VXg-unsplash.jpg" alt="visuel activite marseille">
				<p class="text3"><b>îles du Frioul</b></p>
	
			</div>
		</a> 
	</div>




	<div class="bloc3">
		 <a href="">
			<div class="cardz">
			
				<img class="cardi4" src="img/activites/4_small/kilyan-sockalingum-NR8-cBCN3aI-unsplash.jpg" alt="visuel activite marseille">
				<p class="text4"><b>Parc National des Calanques</b></p>
		
			</div>
		</a> 
	</div>



	<div class="bloc3">

		 <a href="">
			<div class="cardz">

				<img class="cardi5" src="img/activites/4_small/florian-wehde-xW9e8gdotxI-unsplash.jpg" alt="visuel activite marseille">
				<p class="text5"><b>Notre-Dame-de-la-Garde</b></p>
			
			</div>
		</a>
		

		<a href="">
			<div class="cardz">
				
				<img class="cardi6" src="img/activites/4_small/lena-paulin-wH2-EJoDcV0-unsplash.jpg" alt="visuel activite marseille">
				<p class="text6"><b>Parc Longchamps</b></p>
			
			</div>
		</a> 

	</div>

</section>


</main>



<!-- FOOTER -->




	<footer>

			<ul>
				<li>A propos</li>
				<li><a href="#" title="Fonctionnement du site">Fonctionnement du site</a></li>
				<li><a href="#" title="Conditions générales de vente">Conditions générales de vente</a></li>
				<li><a href="#" title="Données et confidentialité">Données et confidentialité</a></li>
			</ul>

			<ul>
				<li>Nos hébergements</li>
				<li><a href="#" title="Charte qualité">Charte qualité</a></li>
				<li><a href="#" title="Soumettre votre hôtel">Soumettre votre hôtel</a></li>
			</ul>

			<ul>
				<li>Assistance</li>
				<li><a href="#" title="Centre d'aide">Centre d'aide</a></li>
				<li><a href="#" title="Nous contacter">Nous contacter</a></li>
			</ul>



		</footer>

	</body>

</html>
