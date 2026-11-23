# Los triples de Gabi

Juego de baloncesto para Gabi: elige ángulo y fuerza (o estira hacia atrás y suelta) y lanza. Tiene niveles con estrellas en dos mundos, entrenamiento y partido contra papá o mamá con sumas.

Se publica con GitHub Pages: https://indalo-apps.github.io/triples-gabi/  
Enlace para instalarlo en el móvil o la tablet: https://indalo-apps.github.io/triples-gabi/?instalar

Sigue la «Guía común para nuestras apps» (proyecto APPS de Claude), en su versión para los juegos de Gabi: se instala como app, funciona sin conexión, se actualiza solo y enseña sus novedades; Ajustes sin autores y aviso infantil.

## Cómo sacar una versión nueva

1. Subir el número en `<meta name="app-version">` (index.html) y en `CACHE` (sw.js).
2. Añadir sus novedades arriba del todo en `NOVEDADES` (index.html), contadas para Gabi.
3. El mensaje del commit empieza por la versión: `v1.2: …`.

El juego comprueba la versión al abrirse, al volver a él y cada 90 segundos, y se recarga solo cuando no hay un tiro, un nivel, un partido ni una racha a medias.

## Gráficos y sonidos

Los sprites (`sprites/`) son los de Canastas de Gabi.

- `sonidos/aplauso.mp3`: «Crowd Cheer and Applause» de DRAGON-STUDIO (Pixabay, licencia de contenido de Pixabay).
- `sonidos/ooh.mp3`: «Crowd Disappointment Reaction» de Universfield (Pixabay, licencia de contenido de Pixabay).

## Aviso

Es un juego para jugar en casa y puede tener algún fallo.
