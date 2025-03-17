Práctica de aula 4 (PA04). Meteorización/intemperización, formas
resultantes, geomorfología climática, karst <small><br>Geomorfología
(GEO-114)<br>Universidad Autónoma de Santo Domingo (UASD)<br>Semestre
2025-01</small>
================
El Tali
2025-03-17

Versión HTML (quizá más legible),
[aquí](https://geomorfologia-master.github.io/meteorizacion-formas-resultantes-geomorfologia-climatica-karst/README.html)

# Fecha/hora de entrega

**[VER PORTAL DE LA
ASIGNATURA](https://github.com/geomorfologia-202501)**

# Práctica de aula 4 (PA04). Meteorización/intemperización, formas resultantes, geomorfología climática, karst

Para fines de referencia, la presentación correspondiente a este tema se
encuentra alojada
[aquí](https://github.com/geomorfologia-master/tema-3-meteorizacion-y-formas-resultantes/blob/gh-pages/meteorizacion_y_formas_resultantes.pdf)
y el libro de texto de la asignatura, Anderson & Anderson (2010).

# EJERCICIO 1: Tasa de denudación

Cálcula la tasa de denudación anual y la denudación al cabo de 30 años,
de tu cuenca elegida (elige una de las siguientes y anúnciala en el
foro):

``` r
# cuenca  tamaño (km cuad.)  densidad rocas (g por cm cúbicos)  tasa transporte sed (kg/año)
# 1             478.71                               2.69                103,435,298.45
# 2             532.13                               2.45                148,569,784.32
# 3             296.46                               3.02                 87,489,625.26
```

Realiza tu cálculo utilizando la fórmula de la tasa de denudación
(*Td*):

*Td = (TTS/A)/ρ*

donde *TTS* es la tasa de transporte de sedimentos, *A* es el área de la
cuenca y *ρ* es la densidad promedio de las rocas de la cuenca.

Redacta, en un máximo de un párrafo, lo siguiente: interpreta tu
resultado comparando con otros casos o respondiendo a preguntas tales
como “Si la *TTS*, *A* o *ρ* fuesen menores o mayores, ¿sería mayor o
menor la *Td*?

IMPORTANTE: no olvides transformar las unidades a un sistema común.

# EJERCICIO 2: Tamaños de clastos de tipos de rocas comunes en distintos tramos de río

``` r
# conjunto            codigo_lugar
# 1                   GJRC_02 y LPRO_03
# 2                   RBAH_01 y LPRO_01
# 3                   AVAV_01 y LPRO_02
```

Como indicador indirecto del potencial erosivo, utiliza los datos de
muestras de clastos tomadas en la cuenca del río Ocoa, que se encuentran
alojados en `data/clastos-longitudes-identificacion.csv`. Compararás el
tamaño de los clastos de los tipos de rocas que sean comunes en tu
conjunto elegido (al elegir, anúncialo en el foro) entre las dos
muestras (filtra según el campo `codigo_lugar`). Cada muestra contiene,
aproximadamente, 100 clastos de distintos tipos de litologías medidos en
tres ejes: largo, ancho y espesor. Una de tus muestras representa el
tramo alto del río, la otra el tramo bajo; en el próximo párrafo te
indico cómo cargar la posición de los puntos de muestras. Compara si los
tamaños en el eje de anchura (campo `ancho_en_mm`) difieren
significativamente entre la muestra de tramo alto y la de tramo bajo.
Para ello, primero determina cuántos clastos de cada roca hay por cada
muestra, luego obtén la media de la anchura, y evalúa dónde dicha media
es mayor o menor, si en la muestra de tramo alto o en la de tramo bajo.
Utiliza una prueba estadística para determinar si se trata de una
diferencia significativa (eso de la significancia, ¿qué es? ¿sirve para
algo aún?) Interpreta el resultado.

Para que puedas visualizar las posiciones de las muestras, descarga el
archivo KML `data/clastos-posiciones-muestras.kml`, el cual contiene los
puntos de muestras. Cárgalo en QGIS o en GoogleEarth. Dado que la
densidad de puntos por unidad de área puede ser muy grande en
determinadas zonas, debes acercarte mucho para visualizar tus puntos
asignados.

Redacta, en un máximo de cuatro párrafos, lo siguiente:

- Introducción, en el que podrías incluir importancia del ejercicio,
  objetivo, justificación.
- Materiales y métodos, donde resumas que materiales usaste (esto
  incluye hasta el teléfono móvil, papel, lápiz, etc.), y las técnicas
  específicas empleadas, que en tu caso son la distancia y el método de
  agrupamiento enseñado.
- Resultado, lo cual supone describir, fríamente, lo que obtuviste.
- Discusión, donde indiques si alcanzaste el objetivo, interpretes el
  resultado, indiques las limitaciones y los posibles trabajos futuros.

# EJERCICIO 3: Macroformas del karst

Elige una macroforma elevada, una deprimida y una aplanada de cualquiera
de los morfosistema kársticos (puedes mezclar entre ellos, por ejemplo,
una elevada de Los Haitises, una deprimida de Jaragua, y una aplanada de
la sierra de Bahoruco), y realiza lo siguiente:

- Documéntate sobre la litología y la evolución en la cartografía
  geológica y geomorfológica de RD, así como en otras fuentes que
  encuentres sobre ellas.
- Realiza un análisis morfométrico de cada una.
- Redacta, en un máximo de cuatro párrafos, lo siguiente:
  - Introducción, en el que podrías incluir importancia del ejercicio,
    objetivo, justificación.
  - Materiales y métodos, donde resumas que materiales usaste (esto
    incluye hasta el teléfono móvil, papel, lápiz, etc.), y las técnicas
    específicas empleadas, que en tu caso son la distancia y el método
    de agrupamiento enseñado.
  - Resultado, lo cual supone describir, fríamente, lo que obtuviste.
  - Discusión, donde indiques si alcanzaste el objetivo, interpretes el
    resultado, indiques las limitaciones y los posibles trabajos
    futuros.

# Referencias

Anderson, R. S., & Anderson, S. P. (2010). Geomorphology: The mechanics
and chemistry of landscapes. Cambridge University Press.
