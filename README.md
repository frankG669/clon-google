# Clon de Google

Este proyecto es un clon simple de la página de inicio de Google. La estructura HTML y los elementos visuales se han replicado con fines educativos y de práctica. No poseo derecho sobre logos e imagenes.



## Contenido

1. [Estructura del Proyecto](#estructura-del-proyecto)
2. [Barra de Navegación](#barra-de-navegación)
3. [Contenido Principal](#contenido-principal)
4. [Pie de Página](#pie-de-página)



## Estructura del proyecto

El código HTML sigue una estructura básica con secciones para el encabezado, el contenido principal y el pie de página. También se incluyen enlaces a fuentes externas y hojas de estilo.

<!-- Código HTML completo aquí -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clon Google</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans&family=Poppins:wght@300;400&family=Recursive:wght@700&family=Roboto:wght@100&display=swap" rel="stylesheet">
    <link rel="icon" href="./images/icons/icon-google.svg">
    <link rel="stylesheet" href="styles/style.css">
</head>
<body>
    <header>
        <nav class="navbar">
            <section class="menu">
                <img class="img-menu" src="./images/icons/menu.svg" alt="Menú de google">
                <a class="nav-links gmail vista-movil" href="#" id="gmail">Todos</a>
                <a class="nav-links  imagenes vista-movil" href="#" id="imagenes">Imágenes</a>
            </section>
            <section class="enlaces">
                <a class="nav-links gmail vista-ordenador" href="#" id="gmail">Gmail</a>
                <a class="nav-links  imagenes vista-ordenador" href="#" id="imagenes">Imágenes</a>
                <a class="nav links" href="#" > <img class="apps-google" src="./images/icons/apps-google.svg" alt="Apps de google"></a>
                <a class="nav-links" href="#" id="acceder">Acceder</a>
            </section>
        </nav>
    </header>
    <main>
        <section class="contenedor">
            <section class="contenedor-imagen-google">
                <section class="imagen-google">
                    <img id="logo" src="./images/google.png" alt="Logo de Google">
                </section>
            </section>
            <section class="busqueda">
                <section class="cuadro-busqueda">
                    <img class="iconos-input-busqueda" src="./images/icons/lupa.svg" alt="Lupa">
                    <input type="text" id="input-search">
                    <a class="accesibilidad" href="#"><img class="iconos-input-busqueda" src="./images/icons/mic.svg" alt="Busqueda por voz"></a>
                    <a class="accesibilidad" href="#"><img class="iconos-input-busqueda" src="./images/icons/lens.svg" alt="Google lens"></a>
                </section>
                <section class="botones">
                    <button class="btn-search" id="search"><a href="#">Buscar con Google</a></button>
                    <button class="btn-search" id="lucky"><a href="#">Voy a tener suerte</a></button>
                </section>
                <section class="tendencias">
                    <section class="titulo-tendencias">
                        <section class="titulo">
                            <h3>Tendencia de búsquedas</h3>
                        </section>
                        <section class="menu-tendencias">
                            <img class="icono-tendencias" src="./images/icons/menu-puntos.svg" alt="">
                        </section>
                    </section>
                    <section class="noti-tendencia">
                        <div class="icono-tendencia">
                            <img class="icono-tendencias" src="./images/icons/tendencia.svg" alt="">
                        </div>
                        <div class="cont-noticia">
                            <p>Lanzamiento cohete espacial SpaceX</p>
                        </div>
                    </section>
                    <section class="noti-tendencia">
                        <div class="icono-tendencia">
                            <img class="icono-tendencias" src="./images/icons/tendencia.svg" alt="">
                        </div>
                        <div class="cont-noticia">
                            <p>Dónde ver miss universo</p>
                        </div>
                    </section>
                    <section class="noti-tendencia">
                        <div class="icono-tendencia">
                            <img class="icono-tendencias" src="./images/icons/tendencia.svg" alt="">
                        </div>
                        <div class="cont-noticia">
                            <p>Alejandro murat hinojosa renuncia</p>
                        </div>
                    </section>
                    <section class="noti-tendencia">
                        <div class="icono-tendencia">
                            <img class="icono-tendencias" src="./images/icons/tendencia.svg" alt="">
                        </div>
                        <div class="cont-noticia">
                            <p>Lotería nacional sorteo especial</p>
                        </div>
                    </section>
                    </section>
                </section>
            </section>
        </section>
    </main>
    <footer>
        <section class="pais">
            <p>México</p>
        </section>
        <section class="opciones">
            <section class="sobre-google">
                <a class="footer-link" href="#">Sobre Google</a>
                <a class="footer-link" href="#">Publicidad</a>
                <a class="footer-link" href="#">Negocios</a>
                <a class="footer-link" href="#">Cómo funciona la Busqueda</a>
            </section>
            <section class="privacidad">
                <a class="footer-link" href="#">Privacidad</a>
                <a class="footer-link" href="#">Condiciones</a>
                <a class="footer-link" href="#">Preferencias</a>
            </section>
        </section>
    </footer>
</body>
</html>



## Barra de navegación

La barra de navegación contiene enlaces a diferentes servicios de Google (ningun enlace redireciona a ninguna página externa o hacia alguna parte del documento), así como opciones para acceder y mostrar el menú. Se adapta a diferentes tamaños de pantalla con enlaces específicos para dispositivos móviles y de escritorio.

<!-- Código HTML del contenido principal -->

<header>
        <nav class="navbar">
            <section class="menu">
                <img class="img-menu" src="./images/icons/menu.svg" alt="Menú de google">
                <a class="nav-links gmail vista-movil" href="#" id="gmail">Todos</a>
                <a class="nav-links  imagenes vista-movil" href="#" id="imagenes">Imágenes</a>
            </section>
            <section class="enlaces">
                <a class="nav-links gmail vista-ordenador" href="#" id="gmail">Gmail</a>
                <a class="nav-links  imagenes vista-ordenador" href="#" id="imagenes">Imágenes</a>
                <a class="nav links" href="#" > <img class="apps-google" src="./images/icons/apps-google.svg" alt="Apps de google"></a>
                <a class="nav-links" href="#" id="acceder">Acceder</a>
            </section>
        </nav>
    </header>

    ![Alt text](image.png)
    ![![![Alt text](image-3.png)](image-2.png)](image-1.png)



## Contenido Principal 

El contenido principal consta de la sección de la imagen de Google, el cuadro de búsqueda y las tendencias de búsqueda(las tendencias de búsqueda están ocultas en la vista de escritorio). La sección de tendencias incluye noticias populares en un diseño sencillo.

<!-- Código HTML del contenido principal -->

<main>
        <section class="contenedor">
            <section class="contenedor-imagen-google">
                <section class="imagen-google">
                    <img id="logo" src="./images/google.png" alt="Logo de Google">
                </section>
            </section>
            <section class="busqueda">
                <section class="cuadro-busqueda">
                    <img class="iconos-input-busqueda" src="./images/icons/lupa.svg" alt="Lupa">
                    <input type="text" id="input-search">
                    <a class="accesibilidad" href="#"><img class="iconos-input-busqueda" src="./images/icons/mic.svg" alt="Busqueda por voz"></a>
                    <a class="accesibilidad" href="#"><img class="iconos-input-busqueda" src="./images/icons/lens.svg" alt="Google lens"></a>
                </section>
                <section class="botones">
                    <button class="btn-search" id="search"><a href="#">Buscar con Google</a></button>
                    <button class="btn-search" id="lucky"><a href="#">Voy a tener suerte</a></button>
                </section>
                <section class="tendencias">
                    <section class="titulo-tendencias">
                        <section class="titulo">
                            <h3>Tendencia de búsquedas</h3>
                        </section>
                        <section class="menu-tendencias">
                            <img class="icono-tendencias" src="./images/icons/menu-puntos.svg" alt="">
                        </section>
                    </section>
                    <section class="noti-tendencia">
                        <div class="icono-tendencia">
                            <img class="icono-tendencias" src="./images/icons/tendencia.svg" alt="">
                        </div>
                        <div class="cont-noticia">
                            <p>Lanzamiento cohete espacial SpaceX</p>
                        </div>
                    </section>
                    <section class="noti-tendencia">
                        <div class="icono-tendencia">
                            <img class="icono-tendencias" src="./images/icons/tendencia.svg" alt="">
                        </div>
                        <div class="cont-noticia">
                            <p>Dónde ver miss universo</p>
                        </div>
                    </section>
                    <section class="noti-tendencia">
                        <div class="icono-tendencia">
                            <img class="icono-tendencias" src="./images/icons/tendencia.svg" alt="">
                        </div>
                        <div class="cont-noticia">
                            <p>Alejandro murat hinojosa renuncia</p>
                        </div>
                    </section>
                    <section class="noti-tendencia">
                        <div class="icono-tendencia">
                            <img class="icono-tendencias" src="./images/icons/tendencia.svg" alt="">
                        </div>
                        <div class="cont-noticia">
                            <p>Lotería nacional sorteo especial</p>
                        </div>
                    </section>
                    </section>
                </section>
            </section>
        </section>
    </main>




## Pie de página

El pie de página contiene información sobre el país y enlaces adicionales sobre Google, así como opciones de privacidad.

<!-- Código HTML del pie de página -->


<footer>
        <section class="pais">
            <p>México</p>
        </section>
        <section class="opciones">
            <section class="sobre-google">
                <a class="footer-link" href="#">Sobre Google</a>
                <a class="footer-link" href="#">Publicidad</a>
                <a class="footer-link" href="#">Negocios</a>
                <a class="footer-link" href="#">Cómo funciona la Busqueda</a>
            </section>
            <section class="privacidad">
                <a class="footer-link" href="#">Privacidad</a>
                <a class="footer-link" href="#">Condiciones</a>
                <a class="footer-link" href="#">Preferencias</a>
            </section>
        </section>
    </footer>



## Contribuciones

Siéntete libre de contribuir, realizar mejoras o informar problemas. ¡Disfruta explorando el clon de Google! 😊.