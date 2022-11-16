<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8" />
		<meta http-equiv="X-UA-Compatible" content="IE=edge" /> <!-- o atributo ten que ver coa compatibilidade do navegador onde se consulta a páxina web (http-equiv=”X-UA-Compatible”), e onde no atributo content, o valor ie=edge fai referencia ao antigo navegador Internet Explorer-->
		<meta name="viewport" content="width=device-width, initial-scale=1.0" /><!-- A metaetiqueta da ventana gráfica indica que o sitio web seguirá o ancho do dispositivo no que estea o usuario, xa sexa un móbil ou o escritorio-->
		
		<link rel="stylesheet" href="snefinal.css" />
		<link rel="stylesheet" media="screen and (max-width:768px)" href="mobile.css" /> <!-- Cando a ventana e menor a 768px toma a referencia de esta stylesheet, así customizamos para o móvil se queremos cambiar o layout-->
		
		
		<title>Portfolio Sne | Bienvenidos !</title>
	</head>
	<body>
			<nav id="navbar">
				<div class="container">
					<a href="#mainheader" class="logo"><img src="img/logosne.png" alt="Logotipo de Sne"/></a>
					<ul>
						<li><a href="#projects">Proyectos</a></li>
						<li><a href="#about">Acerca de mí</a></li>
						<li><a href="#contact">Contacto</a></li>
					</ul>
				</div>
			</nav>
		

		<div id="showcase">
			<div class="container">
					<a href="#projects" class="btn btn-outline">Proyectos</a>
				</div>
			
		</div>
<section id="projects">
			<div class="container">
				<h2>Proyectos en clase</h2>
				<div class="projects-row">
					<div class="projects-row-detail">
						<a href="https://youtu.be/6jkV50sT5z4"> <img src="img/wally.png" height="300" width="auto"
							alt="proxecto buscando a wally" /> </a>
					</div>
					<div class="projects-row-detail">
						<img src="img/trabajo.jpeg" alt="dt" width="auto" height="300" />
					</div>
					<div class="projects-row-detail">
						<a href="https://youtu.be/KzMu0wjb3pM"> <img src="img/medalla.png" alt="medalla" width="auto" height="300" /> </a>
					</div>
				</div>
			</div>
		</section>

		<section id="about">
			<div class="container">
				<h2>Acerca de mí</h2>
				<div class="about-row">
					<div class="about-row-experience">
						<h4>Experiencia</h4>
						<p class="large">Bachillerato de ciencias tecnológicas</p>
						<p class="large">Jugadora profesional de pou</p>
						<p class="large">Doble grado de física y derecho</p>
						<p class="large">Creadora del código html</p>
						<p class="large">Máster en diseño de páginas web como esta</p>
					</div>
					<div class="about-row-me">
						<h4>Acerca de mí</h4>
						<p>
							Curiosa, tranquila y observadora.
							Sin miedo a afrontar retos nuevos y buena manteniendo la calma en situaciones estresantes. Amante de la música, el arte, la lectura y los videojuegos. 
						</p>
					</div>
				</div>
			</div>
		</section>

		<section id="contact">
			<div class="container">
				<h2>Contacto</h2>
				<div class="contact-row">
					<div class="contact-row-icon">
						<img src="img/icon-address.png" alt="" />
						<p>Plaza de Pontevedra</p>
					</div>
					<div class="contact-row-icon">
						<img src="img/icon-mail.png" alt="" />
						<p>sneshankaandres@gmail.com</p>
					</div>
					<div class="contact-row-icon">
						<img src="img/icon-phone.png" alt="" />
						<p>+34 123-456-789</p>
					</div>
				</div>
			</div>
		</section>

		<footer id="mainfooter">
			<div class="container">
				<a href="https://www.instagram.com/snee.02/?next=%2F" class="instagram-follow-button" data-show-count="false"
					>Follow @snee.02</a
				>
				<script async src="https://platform.instagram.com/widgets.js" charset="utf-8"></script>
			</div>
		</footer>
	</body>
</html>
