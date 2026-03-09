# Web informativa – Elecciones Aragón 2026

## Descripción del proyecto

Este proyecto consiste en crear una página web informativa sobre las elecciones autonómicas de Aragón de 2026.

La web muestra información básica del evento como:
- Qué es el evento
- Cuándo se celebra
- Información de los candidatos
- Resultados
- Noticias
- Un formulario de contacto

La página está hecha con HTML y Bootstrap 5 para que se vea bien en móvil, tablet y ordenador.

El proyecto también usa GitHub para guardar los cambios del proyecto.


# Secciones de la página

La página tiene las siguientes partes:

## Navbar
Barra de navegación en la parte superior que permite ir a cada sección de la página.

Contiene enlaces a:
- Inicio
- Candidatos
- Resultados
- Noticias
- Contacto


## Hero
Es la parte principal de la página donde aparece:

- El título del evento
- El logo
- Una pequeña descripción del evento


## Sección Inicio
Explica brevemente de qué trata la página web.


## Sección Candidatos

Aquí aparecen los candidatos principales usando **cards de Bootstrap**.

Se usa el sistema de columnas:

row  
col-md-4  

Esto hace que aparezcan 3 candidatos por fila en pantallas grandes, como el ordenador, y se adapten en móvil.


## Sección Resultados

Se muestra una tabla con los resultados de las elecciones.

Se usan componentes de Bootstrap como:

- table
- table-striped
- table-bordered


## Sección Noticias

Se utiliza un Accordion para mostrar varias noticias sobre las elecciones.

Cada noticia se puede abrir o cerrar.


## Sección Contacto

Formulario donde el usuario puede escribir:

- Nombre
- Correo electrónico
- Mensaje

También tiene un botón para enviar.


## Footer

Parte final de la página con:

- Copyright
- Enlaces legales


# Componentes de Bootstrap utilizados

En este proyecto se han usado:

- Navbar
- Grid (row y col)
- Cards
- Table
- Accordion
- Form
- Button


# Commits realizados

Durante el proyecto se hicieron varios commits:

**Commit 1**  
Creación del proyecto y estructura básica de la página.

**Commit 2**  
Se añadieron los candidatos con tarjetas de Bootstrap.

**Commit 3**  
Se añadió la tabla de resultados y las noticias.

**Commit 4**  
Se añadió el formulario de contacto y el footer.


# Carpeta de capturas

El repositorio incluye una carpeta llamada:

CAPTURAS

Dentro hay una imagen con una captura de la página web terminada.


# Mayor dificultad

La mayor dificultad fue organizar las columnas de Bootstrap para que las tarjetas de los candidatos se vieran bien.

Al principio no se alineaban bien.

La solución fue usar:

row  
col-md-4  

Con esto Bootstrap organiza automáticamente las columnas dependiendo del tamaño de pantalla.
