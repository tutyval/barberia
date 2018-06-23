Premaketado Barberia

para la página usaremos el siguiente diseño
![sketch](img/pagina.jpg) 

para el celular el siguiente diseño
![sketch](img\celular.jpg) 

los colores para el diseño son
para el celular el siguiente diseño
![sketch](colors/colors.png) 

los estilos a utilizar son:
PlayfairDisplay-Blackltalic
PlayfairDisplay-Regular
Roboto-Regular
Roboto-Light

La página deberá contendrá

	 Una barra de navegación con logo:
navbar
	<!-- Image and text -->
	<nav class="navbar navbar-light bg-light">
	<a class="navbar-brand" href="#">
    <img src="/docs/4.1/assets/brand/bootstrap-solid.svg" width="30" height="30" class="d-inline-block align-top" alt="">
    Bootstrap
	</a>
	</nav>
nav
	<ul class="nav justify-content-end">
	<li class="nav-item">
    <a class="nav-link active" href="#">Active</a>
	</li>
	<li class="nav-item">
    <a class="nav-link" href="#">Link</a>
	</li>
	<li class="nav-item">
    <a class="nav-link" href="#">Link</a>
	</li>
	<li class="nav-item">
    <a class="nav-link disabled" href="#">Disabled</a>
	</li>
	</ul>

		Un header con un jumbotron, con boton
Jumbotron
	<div class="jumbotron">
	  <h1 class="display-4">Hello, world!</h1>
	  <p class="lead">This is a simple hero unit, a simple jumbotron-style component for calling extra attention to featured content or information.</p>
	<hr class="my-4">
	<p>It uses utility classes for typography and spacing to space content out within the larger container.</p>
	<a class="btn btn-primary btn-lg" href="#" role="button">Learn more</a>
	</div>
con una imagen de fondo
![imagen de fondo](img\post-image.jpg)
    
		Una entrada con un container con parrafos 
	<div class=container>
	<p></p>
	<p></p>
	<p></p>
	</div>
     
	Un footer

con la firma en la que ira el perfil del autor del artículo en grillas
	<div class="container">
	<div class="row">
    <div class="col">
      1 of 2
    </div>
    <div class="col">
      2 of 2
    </div>
	</div>
con una imagen del autor
![imagen de fondo](img\naomi-thai.png)
con margen redondo
	<img src="img\naomi-thai.png" alt="..." class="rounded-circle">
y parrafo 
	<p></p>
 		
	 Una barra con flechas que permitan ir a las entradas anteriores y siguientes

	<nav aria-label="Page navigation example">
	<ul class="pagination">
    <li class="page-item"><a class="page-link" href="#">Previous</a></li>
    <li class="page-item"><a class="page-link" href="#">1</a></li>
    <li class="page-item"><a class="page-link" href="#">2</a></li>
    <li class="page-item"><a class="page-link" href="#">3</a></li>
    <li class="page-item"><a class="page-link" href="#">Next</a></li>
	</ul>
	</nav>
	
un jumbotron con el logo
	<div class="jumbotron jumbotron-fluid">
	<div class="container">
    <h1 class="display-4">Fluid jumbotron</h1>
    <p class="lead">This is a modified jumbotron that occupies the entire horizontal space of its parent.</p>
	</div>
	</div>

Recuerda que la página web deberá ser responsiva. Toma como referencia el siguiente [mockup](img/barbershop-mobile.png) con la versión móvil.

### Criterios de evaluación:

- Uso de dependencias específicas para la página web
- Utilización de BEM en clases CSS
- Buenas prácticas y uso de identado correcto
- Uso de media queries
- Uso de GIT para versionar el desafío
- Uso de Github Pages
- Creación del repositorio con el desafío
- Creación de README.md con link de página web subida a Github Pages
