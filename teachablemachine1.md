
# MEMORIA DE ENTRENAMIENTO

## INTRODUCCIÓN AL PROBLEMA

Debemos tratar de conseguir con este proyecto clasificar los distintos tipos de basura según los contenedores a los que pertenecen con la máxima precisión posible en el % que aparece. Un ejemplo serán las latas y briks al contenedor amarillo, o al poner una imagen de una botella de vidrio que el programa lo clasifique en el apartado del contenedor verde. En el programa he hecho las clasificaciones de:
- Contenedor amarillo
- Contenedor verde
- Contenedor azul
- Contenedor marrón
- Punto limpio

## Día 1 

He añadido unas cuantas imágenes, pero el % se ha dividido en todos los contenedores de manera que no me dice al que pertenece la basura o se equivoca.
Al repasar y tratar de clasificar correctamente las imágenes en el dia 2, ha mejorado y ya clasifica las imágenes correctamente de manera automática.

## Día 2

 Conjunto 1

Al mejorar la calidad de la clasificación de imágenes en los contenedores ahora da un por ciento muy acertado con las imágenes que debemos usar para probar el funcionamiento del programa.
A medida que voy probando las imágenes para observar el funcionamiento voy arreglando y poniendo también imágenes nuevas en los contenedores. Es la forma más rápida de probar que funciona e ir arreglando por el camino. Por ejemplo:
-Amarillo: el bote de spray en un principio lo clasificaba en el contenedor azul, ahora al colocar un par de imágenes más parecidas lo clasifica en el contenedor amarillo con un 61%. El primer conjunto del amarillo funciona correctamente con todas las imágenes, situándolas todas en el contenedor amarillo.
- Azul: La huevera no funciona bien, sale que pertenece al amarillo y a pesar de tener fotos de hueveras en el azul pienso que por la forma y el color es por lo que lo clasifica aún asi en el amarillo. Al igual ocurre con el rollo de cartón, lo sitúa en el verde por el color marrón de las botellas de cristal probablemente. EL otro objeto funciona correctamente.
- Verde: En este contenedor sitúa todos los objetos del conjunto 1 bien.
- Gris: el pañal lo sitúa en el amarillo, cosa que no entiendo muy bien por qué porque tiene imagenes muy exactas incluidas en el contenedor. Con el corcho ocurre igual.
- Marrón: funciona correctamente con las imágenes del conjunto 1.

 Conjunto 2

Comienzo a colocar imágenes del conjunto 2 y ocurre esto en los diversos contenedores:
- Amarillo: Funcionan correctamente los objetos.
- Azul: El envase de cartón funciona bien, pero la imagen de los papeles no, la sitúa en el organico por la forma desordenada de los papeles al igual que en las imágenes de restos de comida.
- Verde: Funciona correctamente.
- Gris: LA colilla y cucharón los sitúa en al amarillo, creo que por su forma un poco al azar y debido a que no entiende exactamente su color y forma, en cambio el camión lo pone en el azul, tal vez porque parece cartón y haría falta de más imágenes parecidas o de diversos juguetes.

## EJEMPLOS EN IMÁGENES (DÍA 2)
![L](https://github.com/sonieta27/IA-docs/commit/f145f159af6aa0d8124ab7979947b7fbfd3a8cfd)







