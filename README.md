# 0/3
cómic sobre un mundo distópico en el que todos estamos "conectados". Esta serie de cómics es parte del proyecto del [hacklab](http://wiki.hacklab.org.bo/): [Anti Internet.org de Facebook](http://wiki.hacklab.org.bo/index.php?title=Anti_Internet.org_de_Facebook#C.C3.B3mics)

Necesitamos explicarle al mundo por qué internet.org no es tan buena idea... [también puedes contribuír de otras formas](http://wiki.hacklab.org.bo/index.php?title=Anti_Internet.org_de_Facebook)

La idea principal es hacer un cómic compuesto por varias historias que no estén necesariamente relacionadas entre sí (algo así como el universo de Final Fantasy, o como Black Mirror).

Crear un cómic mediante el bazar es una idea interesante, pero aún no sé muy bien cómo llevarla a cabo o_O por el momento, se me ocurren estas ideas:

Cada historia deberá ir en su propia carpeta, y deberá tener esta estructura:
- `story (file)`: La historia del cómic, sirve para crear un script. A diferencia de un script, la historia es un poco más "flexible" (pero es recomendable que no sea ambigua). Se escribe como un cuento, no es necesario que tenga los diálogos "exactos" de lo que los personajes deberían decir, tampoco es necesario que los personajes tengan un nombre, ni que estén bien definidos, tampoco es necesario que sea una lectura amena... sólamente debe expresar, de forma clara, una historia ;) es preferible que sean historias cortas, para poder publicar el cómic lo más antes posible.

- `script (file?)`: El script sirve para crear el cómic "gráfico". Debe describir cada uno de los cuadritos que se van a dibujar, pero en texto. Por cada recuadro, se debe escribir: los personajes involucrados, los diálogos, y una descripción del ambiente en el que ocurren los sucesos.

- `character (folder)`: Esta carpeta contiene los personajes de la historia: Cada personaje debe tener su propia carpeta. Esta carpeta debe contener:
  - `story (file)`: su nombre, su personalidad, y opcionalmente su trasfondo histórico (¿Qué le pasó al personaje antes de que comience la historia?). En resúmen, toda descripción escrita que no tenga que ver con su descripción gráfica.
  - `description (file)`: descripción gráfica del personaje: su altura, colores, razgos étnicos, apariencia física (delgado, robusto, obeso, etc..).
  - `draw (folder)?`: una carpeta con los dibujos del personaje.
    - `TODO (file)`: lista de pedidos de dibujos del personaje.

- `comic (folder)`: aquí van las páginas ya terminadas de cada cómic, enumeradas con 3 dígitos. Ejemplo: `001.svg, 002.svg, ..., 023.svg, 024.svg, ..., 100.svg`

Es recomendable que todas las imágenes tengan fondo transparente!! (y sería genial que también estén en formato `svg` (inkscape puede vectorizar imágenes no vectoriales)... pero también son bienvenidas las imágenes `.png` ;)

Si estás inspirado, y se te ocurren personajes, te recomiendo los pongas en la carpeta `orphan/character`, respetando la estructura de `character (folder)`. Es una buena forma de ayudar! porque alguien que ya tenga una historia, podría usar a tu personaje!

Si se te ocurre alguna idea o razón al rededor de la cuál debería existir un cómic, te recomiendo la pongas en `orphan/idea`, no es necesario que estas ideas tengan una historia... pero son importantes!! servirán de inspiración para crear historias al rededor de ellas :)
