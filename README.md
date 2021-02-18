<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

#¿Cómo ejecutar?

Para la creación de este registro y login, ya que se permitía cualquier framework a elección propia, he utilizado el framework Laravel, recomiendo la instalación de <b><a href="https://laragon.org/download/index.html">Laragon</a></b> para ejecutarlo de forma local, ya que como servidor Apache te trae todo lo necesario (composer, node, etc) para poder ejecutar proyectos en Laravel.

Descargar proyecto (en /laragon/www/), abrir terminal, situarse en el proyecto y ejecutar:

    composer install && npm install

Configurar la base de datos en el archivo .env: 
<ul>
    <li> Copiar .env.example en la misma ruta, renombrar por .env </li>
    <li>Crear una nueva base de datos y establecer el nombre en el archivo .env (DB_DATABASE)</li>
    <li>ejecutar: </li>

    php artisan migrate
<li>Puede acceder al proyecto mediante:</li>

    php artisan serve

<li>O, click derecho encima de Laragon, si ha situado el proyecto en www, puede abrir el proyecto desde ahi y se le abre algo parecido a:</li>

    http://NOMBREPROYECTO.test
Reiniciar Laragon si no se le abre en este formato y probar de nuevo.
</ul>
