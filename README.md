# Introducción

Este repositorio es una actividad de la asignatura IPO (Interacción Personal Ordenador). La asignatura IPO se imparte en las titulaciones de informática de la Universidad de Sevilla.

La actividad tiene como cometido completar el proyecto web inacabado del repositorio atendiendo a unos objetivos que se detallan en este documento.

El proyecto es una aplicacion web que simula un pequeño piano de una octava

Para controlar el sonido que produce el piano, se muestra un menú lateral donde se puede escoger entre varios tipos. La generación del sonido se apoya en la API Web Audio. Una primera introducción a la Web Audio API es
[CSS-tricks: Introducción a la Web AUdio API](https://css-tricks.com/introduction-web-audio-api/). Para profundizar en el tema, se puede consultar [MDN: Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)

# Contenido

La carperta _www_ incluye los ficheros de partida: _index.html_, _script.js_ y _style.css_.

Los cambios se harán fundamentalmente en _style.css_ y _script.js_. En general, consistirán en:

- añadir declaraciones en las reglas CSS preexistentes
- completar funciones vacías en JS. Para su fácil identificación, los nombres de las funciones a completar comenzarán con tres subrayados. Ej.: \_\_\_funcionVacia()

Se admitirán cambios puntuales en la hoja CSS:

- que obedezcan a alguna observación realizada explícitamente en la actividad
- para fomentar la comprensión de la interacción o realzar la estética (márgenes, sombras, redondeado de esquinas, etc.)
- para dotar de un diseño cromático y tipográfico personal al proyecto.

Los cambios en _index.html_ serán admitidos sólo en el caso de que la solución aportada suponga una modificación significativa de la composición del proyecto que requiera dicha intervención.

# Identificación del trabajo:

- script.js: Se actualizará el nombre del equipo de laboratorio en la variable

            const nombreDelEquipoDeLaboratorio = "XXXXXX";

- style.css: Se actualizará el nombre del equipo de laboratorio en la cabecera

             /* EQUIPO <<XXXXXXX>> */

# Objetivos:

El objetivo de la actividad es el aprendizaje de las dos siguientes técnicas:

- Posicionamiento [MDN: position](https://developer.mozilla.org/en-US/docs/Web/CSS/position).
- Web Audio API

Desde el punto de vista del diseño, esta actividad pretende:

- ampliar estrategias para crear composiciones más complejas. El posicionamiento, al alterar la ubicación naturald de los elementos introduce nuevas posibilidades decorativas y de asimetría en los diseños.
- el empleo de los pseudoelementos ::after y ::before en compañía del posicionamiento
- reflexión sobre otros mecanismos alternativos que de facto inducen a una reubicación de elementos (ej. márgenes negativos)

Como objetivos globales (ya tenido en cuenta en actividades anterirores):

- - aprender a combinar de forma oportuna Grid, Flexbox y Flujo Normal
- el uso apropiado de las unidades de medida espaciales en el diseño (em, rem, %, ...)
- la estilización de los elementos como apoyo a la comprensión de la interacción (ej.: ¿cómo hacer notar al usuario que sus acciones son correctas?)
- la flexibilidad en el diseño: _var()_, _calc()_, _clamp(min, preferente, max)_

# Indicaciones

El estilo de codificación en el proyecto se apoya en las siguientes características:

- Atributo id: reservar este atributo para el acceso en JS de elementos HTML
- Atributo class: reservar las clases fundamentalmente para estilizar con CSS los elementos HTML
- [Notación BEM](https://getbem.com/) para seleccionar en CSS los elementos HTML
- Notación hsl() para codificar los colores
- Elemento :root para aunar las variables del diseño cromático y tipográfico
- Variables: Generalizar los estilos CSS mediante el uso de variables var() y la función calc()
- Uso preferente de unidades de longitud flexibles (em, rem, vh, vw, %)
- Criterio homogéneo de organización y nomenclatura
  - En reglas y declaraciones en CSS
  - En variables/funciones en JS
  - Notación camello en los nombres en JS
- Comentarios
  - incluir las referencias utilizadas para el diseño o codificación (MDN, Youtube, Stackoverflow , Coolors, etc.)
  - comentar los aspectos que faciliten la lectura del código cuando sea necesario, evitando los comentarios triviales que se limitan a reescribir el código
