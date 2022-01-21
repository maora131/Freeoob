# Freeoob
 Creación de estructura de un pequeño sitio con Bootstrap/Sass/Parcel
<li>Para este ejercicio empezamos abriendo la consola del laragon creando el archivo freeoob a partir de mkdir. 
<li>Nos posicionaríamos en dicha carpeta y crearíamos documentos (mkdir) y carpetas (touch). También instalaremos el bootstrap para que coja la hoja de estilos. (npm install bootstrap).
<li>Una vez creadas las carpetas meteríamos contenido en .sassrc y en index.html donde ponemos nuestra hoja de estilos y un contenedor donde poner nuestro contenido.
<li>Bootstrap depende de Popper, por lo tanto se añade en el package.json usando npm install @popperjs/core
<li>A continuación se crea la carpeta index.js donde importamos bootstrap y lo añadimos a index.html antes de cerrar <body>
<li>Para hacer las primeras comprobaciones dentro del script de package.json ponemos “start”:”parcel ./src/index.html”,
<li>Al terminar, para ver nuestro sitio ponemos en la consola npm start. Nos dará una dirección (http://localhost:1234/) (En la carpeta disc también se puede visualizar).
<li>Una vez creada nuestra página editamos el style.scss y añadimos:
@import “../node_modules/bootstrap/scss/variables”; (functions-mixins) y a partir de ahí podemos añadir nuestro código css/bootstrap.
<li>Por último, añadimos el formulario, lo procesamos y validamos las diferentes áreas que tiene.
         
         
         
         
![image](https://user-images.githubusercontent.com/91051075/150493547-4c34266e-8dfc-4fda-829f-a3264ee559c9.png)


         
