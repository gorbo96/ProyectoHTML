# ProyectoHTML
## Proyecto de Aprendizaje HTML5
###  Requisitos generales:  
- Ocho páginas en formato html secundarias con temas relacionados a la página principal.  
- Las páginas html, imágenes, audios, videos y otros recursos deberán estar organizadas en carpetas.
- Todas las páginas deberán tener un menú de navegación el cuál, permite al usuario navegar de una manera clara y sencilla entre todas las páginas HTML, tanto la principal como la secundaria.
- Todas las páginas html deben estar estructuradas según la semántica de HTML5.
- Todas las páginas html deben tener una etiqueta <header> la cuál, deberá contener una imagen (logo) relacionada al tema elegido.
- Todas las páginas html deben tener una etiqueta <footer> la cuál, deberá tener la información del estudiante como nombres completos, organización, correo (usar hipervínculo, mailto), teléfono (usar hipervínculo, tel), además deberá tener el símbolo de copyright junto a la leyenda de “Todos los derechos reservados”. Por ejemplo, © Todos los derechos reservados
- Las páginas html deberán tener al menos dos etiquetas <section>, <article> y <aside>.
- Todos los artículos <article> tengan al menos una imagen cada uno.
### Requisitos especificos:
De igual manera, se pide que al menos una de las páginas dentro del contenido de la etiqueta <article>, tengan los siguientes requisitos:
- Una tabla con la siguiente estructura:
![Tabla](HTML5Application/public_html/imagenes/tabla.png)
- Un video de YouTube <iframe>
- Un video con la etiqueta <video>.
- Un audio con la etiqueta <audio>.
- Manejar listas ordenadas o desordenadas con al menos cinco ítems.
- Tener al menos cinco etiquetas de texto.
- Una de las páginas tenga al menos cuatro secciones <section> con tres artículos <article> cada sección. Luego, cada sección debe tener un encabezado <header>, en donde, se ubicaran enlaces que permitan navegar entre los artículos usando id’s
### Desarrollo
#### Pagina index.html
```
<!DOCTYPE html>
<!--Comentario de prueba HTML
5 etiquetas-->
<html lang="ES">      
    <head>
        <title>de TODO un POCO</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta name=”keywords” content="HTML prueba preparacion" />            
    </head>      
    <body>
        <header> <!--ETIQUETA DE CABECERA, PARA LOGO-->
            <h1>Bazar de TODO un POCO</h1> 
            <nav><!--ETIQUETA DE NAVEGACION PARA PODER CAMBIAR ENTRE PAGINAS-->
                <ul>
                    <!--LINKS HACIA PAGINAS EXTERIORES-->
                    <li><a href="Redes.html">Redes Sociales</a></li>
                    <li><a href="Localizaciones.html">Localizaciones</a></li>
                    <li><a href="index.html">Productos de la semana</a></li>
                    <li><a href="Lista.html">Oferta</a></li>
                    <li><a href="Pago.html">Metodos de pago</a></li>
                    <li><a href="Calificacion.html">Califiquenos</a></li>
                    <li><a href="Mision.html">Nosotros</a></li>
                    <li><a href="Credito.html">Credito Directo</a></li>
                </ul>
            </nav>
        <h2>La variedad es nuestra insignia</h2>
        <img src="../imagenes/logo.gif" alt="Icono"/> <!--ETIQUETA DE LOGO-->
        </header>        
        <section id="Productos"> <!--ETIQUETA DE SECCION PARA PRODUCTOS DE LA SEMANA, SECCION INDEPENDIENTE, CON RESPECTIVA IMAGEN-->
            <article>
                <header><h3>Productos de la semana</h3>
                <img src="../imagenes/oferta.jfif" alt="Ofertas"></header>            
            <aside><!--ETIQUETA DE DETALLE DE ARTICULOS-->
                <dl><!--INICIO DE LISTA DE PRODUCTOS DE LA SEMANA-->
                <dt><!--PRODUCTO-->
                    <i><strong>Limpiox</strong></i><!--ETIQUETA DE TEXTO EN CADA DESCRIPCION DE PRODUCTO-->
                </dt>
                <dd><!--ETIQUETA PARA DESCRIPCION-->
                    Producto que desinfecta en un 99% el area.
                </dd>
                <dt>
                    <i><strong>Carne de bobino</strong></i>
                </dt>
                <dd>
                    Carne de bobino de la <u>mejor</u> calidad
                </dd>
                <dt>
                    <i><strong>Leche Deslactosada</strong></i>
                </dt>
                <dd>
                    Pura, fresca
                </dd>
                <dt>
                    <i><strong>Cera para piso</strong></i>
                </dt>
                <dd>
                    Brillo constante para pisos
                </dd>
                <dt>
                    <i><strong>Pan</strong></i>
                </dt>
                <dd>
                    Fresco y delicioso
                </dd>
                <dt>
                    <i><strong>Whisky</strong></i>
                </dt>
                <dd>
                    Sabor britanico puro y de antaño
                </dd>
                <dt>
                    <i><strong>Detergente OMOX</strong></i>
                </dt>
                <dd>
                    Rinde 25% mas que los demas
                </dd>
                <dt>
                    <i><strong>Saborizalo!</strong></i>
                </dt>
                <dd>
                    Te saborizado. Delicioso al paladar
                </dd>
                <dt>
                    <i><strong>Queso Fabiola</strong></i>
                </dt>
                <dd>
                    Delicioso, fresco, <q>artesanal</q>
                </dd>
            </dl>
            </aside>
            </article>
        </section>
        <section><!--ETIQUETA DE SECCION, NUEVOS PRODUCTOS,SECCION INDEPENDIENTE-->
            <article><!--ETIQUETA DE CABECERA, PARA LOGO-->
                <header><h3>Nuevos Productos</h3>
                    <img src="../imagenes/new.webp" alt="Nuevos Productos"></header>
                <aside><!--ETIQUETA DE DESCRIPCION DE ARTICULO-->
                    <dl><!--ETIQUETA DE LISTADO DE PRODUCTOS-->
                        <dt>
                            <i><strong>Leche de cabra</strong></i>
                        </dt>
                        <dd>
                            Nuevo producto, 100% natural, delicioso
                        </dd>                         
                        <dt>
                            <i><strong>Queso de cabra</strong></i>
                        </dt>
                        <dd>
                            Nuevo producto, 100% natural, delicioso
                        </dd>
                    </dl>
                </aside>                    
            </article>
        </section>
        <footer>Martin Bojorque&#8226;&nbsp;<a href="mailto:atencionclidnte@comdetup.com">Email:atencioncliente@comdetup.com</a>&#8226;<a href="tel:+5932543678">Telf:(593)2543678</a>&#8226;Todos los derechos reservados&#169;</footer><!--ETIQUETA DE PIE DE PAGINA CON CADA ITEM REUQERIDO-->
    </body>
</html>  
```
#### Pagina Lista.html
```
<!DOCTYPE html>
<html>
    <head>
        <title>Productos COMDETUP</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
    <body>
        <header><!--ETIQUETA DE CABECERA, PARA LOGO-->
            <h1>Lista Productos COMDETUP</h1> 
            <nav><!--ETIQUETA DE NAVEGACION PARA PODER CAMBIAR ENTRE PAGINAS-->
                <ul>
                    <!--LINKS HACIA PAGINAS EXTERIORES-->
                    <li><a href="Redes.html">Redes Sociales</a></li>
                    <li><a href="Localizaciones.html">Localizaciones</a></li>
                    <li><a href="index.html">Productos de la semana</a></li>
                    <li><a href="Lista.html">Oferta</a></li>
                    <li><a href="Pago.html">Metodos de pago</a></li>
                    <li><a href="Calificacion.html">Califiquenos</a></li>
                    <li><a href="Mision.html">Nosotros</a></li>
                    <li><a href="Credito.html">Credito Directo</a></li>
                </ul>
            </nav>
            <img src="../imagenes/logo.gif" alt="Icono"/><!--ETIQUETA DE LOGO-->
        </header>
        <section><!--ETIQUETA DE SECCION SUPERMERCADO, SECCION INDEPENDIENTE-->
            <header><!--ETIQUETA DE CABECERA DE SECCION-->
                <h2>Supermecado</h2>
                <nav><!--ETIQUETA DE NAVEGACION ENTRE SUBSECCIONES DE LA SECCION SUPERMERCADO-->
                    <ul>
                        <li><a href="Lista.html#Embutidos">Embutidos</a></li><!--ETIQUETA DE REFERENCIA A SUBSECCION-->
                    </ul>
                    <ul>
                        <li><a href="Lista.html#Lacteos">Lacteos</a></li>
                    </ul>
                    <ul>
                        <li><a href="Lista.html#Aseo">Aseo</a></li>
                    </ul>
                </nav>                
            </header>
            <article id="Embutidos"><!--ETIQUETA DE SUBSECCION O ARTUCULO DE EMBUTIDOS, IMAGEN CORRESPONDIENTE Y DESCRIPCION-->
                <h3>Embutidos</h3>
                <img src="../imagenes/embutidos.jpg" alt="Embutidos"><!--ETIQUETA DE IMAGEN-->
                <aside><!--ETIQUETA DE DESCRIPCION DE ARTICULO-->
                    <p>Aqui podra encontrar los mejores y frescos embutidos</p>
                </aside>
            </article>
            <article id="Lacteos"><!--ETIQUETA DE SUBSECCION O ARTUCULO DE LACTEOS, IMAGEN CORRESPONDIENTE Y DESCRIPCION-->
                <h3>Lacteos</h3>
                <img src="../imagenes/lacteos.png" alt="Lacteos">
                <aside>
                    <p>Aqui podra encontrar los mejores y frescos lacteos locales</p>
                </aside>
            </article>
            <article id="Aseo"><!--ETIQUETA DE SUBSECCION O ARTUCULO DE ASEO, IMAGEN CORRESPONDIENTE Y DESCRIPCION-->
                <h3>Aseo</h3>
                <img src="../imagenes/aseo.png" alt="Aseo">
                <aside>
                    <p>Una gran variedad productos de aseo personal lo esperan</p>
                </aside>
            </article>
        </section>
        <section><!--ETIQUETA DE SECCION DE FERRETERIA, SECCION INDEPENDIENTE-->
            <header><!--ETIQUETA DE CABECERA DE SECCION DE FERRETERIA-->
                <h2>Ferreteria</h2>
                <nav><!--ETIQUETA DE NAVEGACION DENTRO DE SUBSECCION FERRETERIA-->
                    <ul>
                        <li><a href="Lista.html#Construccion">Construccion</a></li>
                    </ul>
                    <ul>
                        <li><a href="Lista.html#Electricidad">Electricidad</a></li>
                    </ul>
                    <ul>
                        <li><a href="Lista.html#Decoraciones">Decoraciones</a></li>
                    </ul>
                </nav>                
            </header>            
            <article id="Construccion"><!--ETIQUETA DE SUBSECCION O ARTUCULO DE CONSTRUCCION, IMAGEN CORRESPONDIENTE Y DESCRIPCION-->
                <h3>Construccion</h3>
                <img src="../imagenes/construccion.png" alt="Construccion">
                <aside>
                    <p>Aqui podra encontrar llas mejores herraminetas y suministros para su contruccion</p>
                </aside>
            </article>
            <article id="Electricidad"><!--ETIQUETA DE SUBSECCION O ARTUCULO DE ELECTRICIDAD, IMAGEN CORRESPONDIENTE Y DESCRIPCION-->
                <h3>Electricidad</h3>
                <img src="../imagenes/electricidad.gif" alt="Electricidad">
                <aside>
                    <p>Aqui podra encontrar todo lo relacionado a los sistemas electricos</p>
                </aside>
            </article>
            <article id="Decoraciones"><!--ETIQUETA DE SUBSECCION O ARTUCULO DE DECORACIONES, IMAGEN CORRESPONDIENTE Y DESCRIPCION-->
                <h3>Decoraciones</h3>
                <img src="../imagenes/decoraciones.png" alt="Decoraciones">
                <aside>
                    <p>Las mejores decoraciones a precios increibles</p>
                </aside>
            </article>
        </section>
        <section><!--ETIQUETA DE SECCION DE PAPELERIA, SECCION INDEPENDIENTE-->
            <header><!--ETIQUETA DE CABECERA DE SECCION-->
                <h2>Papeleria</h2>
                <nav><!--ETIQUETA DE NAVEGACION ENTRE SUBSECCIONES O ARTUCULOS DE PAPELERIA-->
                    <ul>
                        <li><a href="Lista.html#Libreria">Libreria</a></li>
                    </ul>
                    <ul>
                        <li><a href="Lista.html#Manualidades">Manualidades</a></li>
                    </ul>
                    <ul>
                        <li><a href="Lista.html#Oficina">Oficina</a></li>
                    </ul>
                </nav>                
            </header>            
            <article id="Libreria"><!--ETIQUETA DE SUBSECCION O ARTUCULO DE LIBRERIA, IMAGEN CORRESPONDIENTE Y DESCRIPCION-->
                <h3>Libreria</h3>
                <img src="../imagenes/libreria.png" alt="Libreria">
                <aside>
                    <p>Libros de todo genero y autor</p>
                </aside>
            </article><!--ETIQUETA DE SUBSECCION O ARTUCULO DE MANUALIDADES, IMAGEN CORRESPONDIENTE Y DESCRIPCION-->
            <article id="Manualidades">
                <h3>Manualidades</h3>
                <img src="../imagenes/manualidades.jpg" alt="Manualidades">
                <aside>
                    <p>Todo para que la imaginacion no pare</p>
                </aside>
            </article>
            <article id="Oficina"><!--ETIQUETA DE SUBSECCION O ARTUCULO DE OFICINA, IMAGEN CORRESPONDIENTE Y DESCRIPCION-->
                <h3>Oficina</h3>
                <img src="../imagenes/oficina.png" alt="Oficina">
                <aside>
                    <p>Productos de oficina con los mejores precios</p>
                </aside>
            </article>
        </section>
        <section><!--ETIQUETA DE SECCION TECNOLOGIA, SECCION INDEPENDIENTE-->
            <header><!--ETIQUETA DE CABECERA DE SECCION-->
                <h2>Tecnologia</h2>
                <nav><!--ETIQUETA DE NAVEGACION ENTRE SUBSECCIONES O ARTUCULOS DE TECNOLOGIA-->
                    <ul>
                        <li><a href="Lista.html#Audio">Audio</a></li>
                    </ul>
                    <ul>
                        <li><a href="Lista.html#Video">Video</a></li>
                    </ul>
                    <ul>
                        <li><a href="Lista.html#Dispositivos">Dispositivos</a></li>
                    </ul>
                </nav>                
            </header>            
            <article id="Audio"><!--ETIQUETA DE SUBSECCION O ARTUCULO DE AUDIO, IMAGEN CORRESPONDIENTE Y DESCRIPCION-->
                <h3>Audio</h3>
                <img src="../imagenes/audio.png" alt="Audio">
                <aside>
                    <p>Todo lo necesario para los sistemas de audio</p>
                </aside>
            </article>
            <article id="Video"><!--ETIQUETA DE SUBSECCION O ARTUCULO DE VIDEO, IMAGEN CORRESPONDIENTE Y DESCRIPCION-->
                <h3>Video</h3>
                <img src="../imagenes/video.png" alt="Video">
                <aside>
                    <p>Todo lo necesario para los sistemas de video</p>
                </aside>
            </article>
            <article id="Dispositivos"><!--ETIQUETA DE SUBSECCION O ARTUCULO DE DISPOSITIVOS, IMAGEN CORRESPONDIENTE Y DESCRIPCION-->
                <h3>Dispositivos</h3>
                <img src="../imagenes/dispositivos.png" alt="Dispositivos">
                <aside>
                    <p>Aparatos de uso diario en oferta</p>
                </aside>
            </article>
        </section>
        <footer>Martin Bojorque&#8226;&nbsp;<a href="mailto:atencionclidnte@comdetup.com">Email:atencioncliente@comdetup.com</a>&#8226;<a href="tel:+5932543678">Telf:(593)2543678</a>&#8226;Todos los derechos reservados&#169;</footer><!--ETIQUETA DE PIE DE PAGINA CON CADA ITEM REUQERIDO-->
    </body>
</html>
```
#### Pagina Localizaciones.html
```
<!DOCTYPE html>
<html>
    <head>
        <title>Localidades COMDETUP</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
    <body>
        <header><!--ETIQUETA DE CABECERA, PARA LOGO-->
            <audio src="../audio/AMiLindoEcuador.mp3" preload="auto" controls autoplay></audio><!--ETIQUETA DE AUDIO, PATH RELATIVO, ACOREDE A ORGANIZACION EN CARPETAS, CON CONTROLES PARA MANEJAR REPRODUCCION-->
            <h1>Localidades</h1>            
           <nav><!--ETIQUETA DE NAVEGACION PARA PODER CAMBIAR ENTRE PAGINAS-->
                <ul>
                     <!--LINKS HACIA PAGINAS EXTERIORES-->
                    <li><a href="Redes.html">Redes Sociales</a></li>
                    <li><a href="Localizaciones.html">Localizaciones</a></li>
                    <li><a href="index.html">Productos de la semana</a></li>
                    <li><a href="Lista.html">Oferta</a></li>
                    <li><a href="Pago.html">Metodos de pago</a></li>
                    <li><a href="Calificacion.html">Califiquenos</a></li>
                    <li><a href="Mision.html">Nosotros</a></li>
                    <li><a href="Credito.html">Credito Directo</a></li>
                </ul>
            </nav>
            <img src="../imagenes/logo.gif" alt="Icono"/> <!--ETIQUETA PARA LOGO-->
        </header>
        <section id="Cuenca"> <!--ETIQUETA PARA SECCION CUENCA, SECCION INDEPENDIENTE-->
            <article> <!--ARTICULO SOBRE LOCALIZACION CUENCA CON FOTO CORRESPONDIENTE-->
                <img src="../imagenes/cuenca.jpg" alt="Cuenca"/>
                <aside>
                    <p>Cuenca:Av Don Alonso y Fray Roberto Saliente</p>
                </aside>                    
            </article>            
        </section>
        <section id="Guayaquil"><section id="Cuenca"> <!--ETIQUETA PARA SECCION GUAYAQUIL, SECCION INDEPENDIENTE-->
            <article><article> <!--ARTICULO SOBRE LOCALIZACION CUENCA CON FOTO CORRESPONDIENTE-->
                <img src="../imagenes/guayaquil.jpeg" alt="Guayaquil"/>
                <aside>
                    <p>Cuenca:Av 19 de Octubre y Simon Calar</p>
                </aside>                    
            </article>            
        </section>
        <footer>Martin Bojorque&#8226;&nbsp;<a href="mailto:atencionclidnte@comdetup.com">Email:atencioncliente@comdetup.com</a>&#8226;<a href="tel:+5932543678">Telf:(593)2543678</a>&#8226;Todos los derechos reservados&#169;</footer><!--ETIQUETA DE PIE DE PAGINA CON CADA ITEM REUQERIDO-->
    </body>
</html> 
```
#### Pagina Pago.html     
```
<!DOCTYPE html>
<html>
    <head>
        <title>Pagos COMDETUP</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
    <body>
        <header><!--ETIQUETA DE CABECERA, PARA LOGO-->
            <h1>Metodos de pago</h1>
            <nav><!--ETIQUETA DE NAVEGACION PARA PODER CAMBIAR ENTRE PAGINAS-->
                <ul>
                     <!--LINKS HACIA PAGINAS EXTERIORES-->
                    <li><a href="Redes.html">Redes Sociales</a></li>
                    <li><a href="Localizaciones.html">Localizaciones</a></li>
                    <li><a href="index.html">Productos de la semana</a></li>
                    <li><a href="Lista.html">Oferta</a></li>
                    <li><a href="Pago.html">Metodos de pago</a></li>
                    <li><a href="Calificacion.html">Califiquenos</a></li>
                    <li><a href="Mision.html">Nosotros</a></li>
                    <li><a href="Credito.html">Credito Directo</a></li>
                </ul>
            </nav>
            <img src="../imagenes/logo.gif" alt="Icono"/> <!--ETIQUETA DE LOGO-->
        </header>
        <section> <!--ETIQUETA DE SECCION DE TIPOS DE PAGO, SECCION INDEPENDIENTE-->
            <article>
                <img src="../imagenes/dinero.png" alt="Icono"/>  <!--ETIQUETA DE ARTICULO PARA FORMAS DE PAGO, IMAGEN CORRESPONDIENTE-->
                <aside>
                    <ul> <!--ETIQUETA PARA LISTA DE FORMAS DE PAGO-->                    
                        <li>Efectivo</li>
                        <li>Cheque</li>
                        <li>Credito Directo</li>
                        <li>Tarjeta de Debido</li>
                        <li>Tarjeta de Credito</li>
                    </ul>                
                </aside>                
            </article>            
        </section>
        <section> <!--SECCION DE BANCOS AFILIADOS-->
            <article>
                <h2>Bancos</h2>
                <img src="../imagenes/bancos.png" alt="Icono"/> <!--ETIQUETA DE ARTICULO PARA BANCOS, IMAGEN CORRESPONDIENTE--> 
                <aside>
                    <ul><!--ETIQUETA PARA LISTA DE BANCOS AFILIADOS-->                      
                        <li>Austro</li>
                        <li>Machala</li>
                        <li>Pacifico</li>
                        <li>JEP</li>
                        <li>Guayaquil</li>
                    </ul>                
                </aside>                
            </article>            
        </section>
        <footer>Martin Bojorque&#8226;&nbsp;<a href="mailto:atencionclidnte@comdetup.com">Email:atencioncliente@comdetup.com</a>&#8226;<a href="tel:+5932543678">Telf:(593)2543678</a>&#8226;Todos los derechos reservados&#169;</footer><!--ETIQUETA DE PIE DE PAGINA CON CADA ITEM REUQERIDO-->
    </body>
</html>      
```
#### Pagina Redes.html  
```
<!DOCTYPE html>
<html>
    <head>
        <title>Redes Sociales COMDETUP</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">        
        <meta name=”keywords” content="HTML prueba preparacion" />        
    </head>
    <body>
        <header><!--ETIQUETA DE CABECERA, PARA LOGO-->
            <h1>Redes Sociales</h1>
            <video preload controls autoplay><!--ETIQUETA DE VIDEO, PATH RELATIVO, ACOREDE A ORGANIZACION EN CARPETAS, CON CONTROLES PARA MANEJAR REPRODUCCION-->
                <source src="../video/video.mp4" type="video/mp4">            
            Tu navegador no implementa el elemento <code>video</code>.
            </video>
            <nav><!--ETIQUETA DE NAVEGACION PARA PODER CAMBIAR ENTRE PAGINAS-->
                <ul>
                    <!--LINKS HACIA PAGINAS EXTERIORES-->
                    <li><a href="Redes.html">Redes Sociales</a></li>
                    <li><a href="Localizaciones.html">Localizaciones</a></li>
                    <li><a href="index.html">Productos de la semana</a></li>
                    <li><a href="Lista.html">Oferta</a></li>
                    <li><a href="Pago.html">Metodos de pago</a></li>
                    <li><a href="Calificacion.html">Califiquenos</a></li>
                    <li><a href="Mision.html">Nosotros</a></li>
                    <li><a href="Credito.html">Credito Directo</a></li>
                </ul>
            </nav>
            <img src="../imagenes/logo.gif" alt="Icono"/><!--ETIQETA PARA LOGO-->
            <p>Bienvenidos a nuestra seccion de redes sociales.</p>
            <p>Te invitamos a seguirnos en nuestras redes sociales y a compartir nuestro contenido</p>            
        </header>
        <section id="Twitter"><!--SECCION TWITTER,SECCION INDEPENDIENTE-->
            <article>
                <nav><!--LINKS HACIA PAGINAS EXTERIORES, CON IMAGEN COMO ENLACE, ENLACE HTTP A TWITTER-->
                    <a href="http://www.twitter.com"><img src="../imagenes/twitter.png" alt="tuiter" /></a>                    
                </nav>
                <aside><!--DESCRIPCION DE ARTICULO-->
                    <p>Twitter</p>
                    <p>Siguenos para noticias diarias,degustaciones y promociones semanales,sorteos entre clientes afiliados, entre otros.</p>
                    <p>&#64;DeTodoUnPoco</p>
                </aside>
            </article>      
        </section>        
        <section id="Facebook"><!--SECCION FACEBOOK,SECCION INDEPENDIENTE-->
            <article>
                <nav><!--LINKS HACIA PAGINAS EXTERIORES, CON IMAGEN COMO ENLACE, ENLACE HTTP A FACEBOOK-->
                    <a href="http://www.facebook.com"><img src="../imagenes/facebook.png" alt="feisbuk" /></a>                   
                </nav>
                <aside><!--DESCRIPCION DE ARTICULO-->
                    <p>Facebook Siguenos para noticias diarias,degustaciones y promociones semanales,sorteos entre clientes afiliados,eventos promocionales,informacion sobre los locales.</p>
                    <p>&#64;DeTodoUnPoco</p>
                </aside>
            </article>      
        </section>
        <footer>Martin Bojorque&#8226;&nbsp;<a href="mailto:atencionclidnte@comdetup.com">Email:atencioncliente@comdetup.com</a>&#8226;<a href="tel:+5932543678">Telf:(593)2543678</a>&#8226;Todos los derechos reservados&#169;</footer><!--ETIQUETA DE PIE DE PAGINA CON CADA ITEM REUQERIDO-->
    </body>
</html>        
```
#### Pagina Credito.html
```
<!DOCTYPE html>
<html>
    <head>
        <title>Credito Directo COMDETUP</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
    <body>
        <header><!--ETIQUETA DE CABECERA, PARA LOGO-->
            <h1>Credito Directo COMDETUP</h1> 
            <nav><!--ETIQUETA DE NAVEGACION PARA PODER CAMBIAR ENTRE PAGINAS-->
                <ul>
                    <!--LINKS HACIA PAGINAS EXTERIORES-->
                    <li><a href="Redes.html">Redes Sociales</a></li>
                    <li><a href="Localizaciones.html">Localizaciones</a></li>
                    <li><a href="index.html">Productos de la semana</a></li>
                    <li><a href="Lista.html">Oferta</a></li>
                    <li><a href="Pago.html">Metodos de pago</a></li>
                    <li><a href="Calificacion.html">Califiquenos</a></li>
                    <li><a href="Mision.html">Nosotros</a></li>
                    <li><a href="Credito.html">Credito Directo</a></li>
                </ul>
            </nav>
            <img src="../imagenes/logo.gif" alt="Icono"/><!--ETIQUETA PARA LOGO-->
        </header>
        <section><!--ETIQUETA PARA SECCION CREDITO DIRECTO, SECCION INDEPENDIENTE, CON IMAGEN CORRESPONDIENTE-->
            <article>
                <img src="../imagenes/credito.png" alt="Credito"/><!--ETIQETA PARA LOGO-->
                <aside>
                    <p>Nuestro credito directo te permite comprar en nuestros locales, sin efectivo, con seguridad BIOMETRICA. Para que nada te detenga de obtener lo que quieras.</p>                    
                        <table border="2" frame="box"><!--ETIQUETA PARA TABLA DE INTERES DE CREDITO-->
                            <caption><!--ETIQUETA PARA TITULO DE TABLA-->
                                Tabla de interes para el servicio de credito directo
                            </caption>
                            <thead ><!--ETIQUETA PARA CABECERA DE TABLA, CORRESPONDIENTE CON LA IMAGEN ANTES PRESENTADA-->
                                <tr>
                                    <th rowspan="2">Tipo de membresia</th><!--ETIQUETA PARA CELDA CON DIMENSIONES ESPECIALES-->
                                    <th colspan="2">Años de membresia</th><!--ETIQUETA PARA CELDA CON DIMENSIONES ESPECIALES-->
                                </tr>
                                <tr>
                                    <th>Menos de cinco años de membresia</th><!--ETIQUETA PARA CELDA-->
                                    <th>Cinco o mas años de membresia</th><!--ETIQUETA PARA CELDA-->
                                </tr>                                    
                            </thead>
                            <tbody><!--ETIQUETA PARA CUERPO DE TABLA-->
                                <tr>
                                    <th>Gold</th><!--ETIQUETA PARA CELDA CON TEXTO ESPECIAL-->
                                    <td>3%</td>
                                    <td>2%</td>
                                </tr>
                                <tr>
                                    <th>Platinum</th><!--ETIQUETA PARA CELDA CON TEXTO ESPECIAL-->
                                    <td>2%</td>
                                    <td>1.5%</td>
                                </tr>
                            </tbody>                            
                            <tfoot><!--ETIQUETA PARA FINAL DE TABLAL-->
                                <tr>
                                    <td colspan="3">Las codiciones de cada usuario deben ser verificadas por el establecimiento y estan sujatas a su aprobacion.</td>
                                </tr>
                            </tfoot>
                        </table>                    
                </aside>                    
            </article>
        </section>
        <section><!--ETIQUETA PARA SECCION DE PREREQUISITOS, SECCION INDEPENDIENTE, CON IMAGEN CORRESPONDIENTE-->
            <article>
                <img src="../imagenes/logo.gif" alt="Logo"/>
                <aside>
                    Para poder acceder a este servicio lo necesario es:
                        <ul><!--ETIQUETA PARA LISTA DE PREREQUISITOS-->
                            <li>Tu cedula de identidad</li>
                            <li>Una cueta de ahorros</li>
                            <li>Llenar un formulario</li>
                        </ul>
                        Y listo tienes tu credito.El proceso puede tomar de 24 a 72 horas.                    
                </aside>
            </article>
        </section>
    <footer>Martin Bojorque&#8226;&nbsp;<a href="mailto:atencionclidnte@comdetup.com">Email:atencioncliente@comdetup.com</a>&#8226;<a href="tel:+5932543678">Telf:(593)2543678</a>&#8226;Todos los derechos reservados&#169;</footer><!--ETIQUETA DE PIE DE PAGINA CON CADA ITEM REUQERIDO-->
    </body>
</html>        
```
#### Pagina Calificacion.html 
```
<!DOCTYPE html>
<html>
    <head>
        <title>Califiquenos COMDETUP</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
    <body>
        <header><!--ETIQUETA DE CABECERA, PARA LOGO-->
            <h1>Califiquenos</h1> 
            <nav><!--ETIQUETA DE NAVEGACION PARA PODER CAMBIAR ENTRE PAGINAS-->
                <ul>
                    <!--LINKS HACIA PAGINAS EXTERIORES-->
                    <li><a href="Redes.html">Redes Sociales</a></li>
                    <li><a href="Localizaciones.html">Localizaciones</a></li>
                    <li><a href="index.html">Productos de la semana</a></li>
                    <li><a href="Lista.html">Oferta</a></li>
                    <li><a href="Pago.html">Metodos de pago</a></li>
                    <li><a href="Calificacion.html">Califiquenos</a></li>
                    <li><a href="Mision.html">Nosotros</a></li>
                    <li><a href="Credito.html">Credito Directo</a></li>
                </ul>
            </nav>
            <img src="../imagenes/logo.gif" alt="Icono"/>
        </header>
        <section><!--ETIQUETA PARA SECCION DEL VIDEO DE YOUTUBE-->
            <article><!--ETIQUETA PARA ARTICULO CON DESCRIPCION DEL VIDEO DE YOUTUBE-->
                <iframe width="560" height="315" src="https://www.youtube.com/embed/JwBf_9M1S7k"></iframe><!--ETIQUETA IFRAME PARA UN VIDEO EMBEBIDO DE YOUTUBE CON ESPECIFICACIONES DE DIMENSIONES-->
            </article>
            <aside>
                <p> Un video explicativo de una fuente externa (Youtube).PATROCINADOR</p>
            </aside>
        </section>
        <section><!--ETIQUETA PARA SECCION EXPLICACIOND DE LAS CALIFICACIONES, CON IMAGEN CORRESPONDIENTE-->
            <article>
                <img src="../imagenes/usuarios.png" alt="Icono"/>
            </article>
            <aside>
                <p>Nuestra seccion de calificaciones se encuentra implementada para mayor comodidad sobre cada una de las redes sociales de la empresa.</p>
            </aside>
        </section>
        <footer>Martin Bojorque&#8226;&nbsp;<a href="mailto:atencionclidnte@comdetup.com">Email:atencioncliente@comdetup.com</a>&#8226;<a href="tel:+5932543678">Telf:(593)2543678</a>&#8226;Todos los derechos reservados&#169;</footer><!--ETIQUETA DE PIE DE PAGINA CON CADA ITEM REUQERIDO-->
    </body>
</html>    
```
#### Pagina Nosostros.html         
```
<!DOCTYPE html>
<html>
    <head>
        <title>Nosotros COMDETUP</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
    <body>
        <header><!--ETIQUETA DE CABECERA, PARA LOGO-->
            <h1>Nosotros</h1> 
            <nav><!--ETIQUETA DE NAVEGACION PARA PODER CAMBIAR ENTRE PAGINAS-->
                <ul>
                    <!--LINKS HACIA PAGINAS EXTERIORES-->
                    <li><a href="Redes.html">Redes Sociales</a></li>
                    <li><a href="Localizaciones.html">Localizaciones</a></li>
                    <li><a href="index.html">Productos de la semana</a></li>
                    <li><a href="Lista.html">Oferta</a></li>
                    <li><a href="Pago.html">Metodos de pago</a></li>
                    <li><a href="Calificacion.html">Califiquenos</a></li>
                    <li><a href="Mision.html">Nosotros</a></li>
                    <li><a href="Credito.html">Credito Directo</a></li>
                </ul>
            </nav>
            <img src="../imagenes/logo.gif" alt="Icono"/>
        </header>
        <section><!--ETIQUETA DE SECCION MISION, SECCION INDEPENDIENTE, CON IMAGEN CORRESPONDIENTE -->
            <article>
                <img src="../imagenes/mision.png" alt="Mision"/>
            </article>
            <aside><!--DESCRIPCION DE ARTICULO-->
                <p>Convertirnos en una franquicia nacional, comprometida con nuestros clientes</p>
            </aside>
        </section>
        <section><!--ETIQUETA PARA SECCION DE VISION, SECCION INDEPENDIENTE, CON IMAGEN CORERSPONDIENTE-->
            <article>
                <img src="../imagenes/vision.png" alt="Vision"/>
            </article>
            <aside>
                <p>Proveer alimentos, productos de primera necesidad, y otros articulos localcmente.</p>
            </aside>
        </section><!--DESCRIPCION DE ARTICULO-->
        <footer>Martin Bojorque&#8226;&nbsp;<a href="mailto:atencionclidnte@comdetup.com">Email:atencioncliente@comdetup.com</a>&#8226;<a href="tel:+5932543678">Telf:(593)2543678</a>&#8226;Todos los derechos reservados&#169;</footer><!--ETIQUETA DE PIE DE PAGINA CON CADA ITEM REUQERIDO-->
    </body>
</html>
```
