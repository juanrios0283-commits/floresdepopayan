# Clasificación de fotografías recibidas

Las 34 fotos del ZIP de WhatsApp fueron clasificadas automáticamente con un modelo de visión (CLIP) y agrupadas en las categorías de la web. La **confianza** es el puntaje del modelo (0 a 1): cuanto más bajo, más conviene revisarlo.

> Esta clasificación es una ayuda, no una verdad absoluta. Si alguna foto está mal ubicada, dime el número y la categoría correcta y la muevo.

## Resumen

| Categoría | Fotos | Archivos |
|---|---:|---|
| Ramos y bouquets | 22 | `ramos-01.jpg` … `ramos-22.jpg` |
| Arreglos y centros | 8 | `arreglos-01.jpg` … `arreglos-08.jpg` |
| Bodas | 1 | `bodas-01.jpg` |
| Condolencias | 3 | `condolencias-01.jpg` … `condolencias-03.jpg` |

## Detalle

| # | Archivo original | Categoría | Tipo detectado | Confianza |
|---:|---|---|---|---:|
| 1 | 11.37.17 PM.jpeg | Bodas | Ramo de novia | 0.761 |
| 2 | 11.37.17 PM (1).jpeg | Ramos | Ramo de mano | 0.308 |
| 3 | 11.37.17 PM (2).jpeg | Ramos | Ramo de mano | 0.542 |
| 4 | 11.37.17 PM (3).jpeg | Ramos | Ramo de mano | 0.324 |
| 5 | 11.37.17 PM (4).jpeg | Ramos | Ramo de mano | 0.373 |
| 6 | 11.37.17 PM (5).jpeg | Ramos | Ramo de mano | 0.682 |
| 7 | 11.37.17 PM (6).jpeg | Ramos | Ramo redondo de rosas | 0.580 |
| 8 | 11.37.17 PM (7).jpeg | Ramos | Ramo redondo de rosas | 0.778 |
| 9 | 11.37.17 PM (8).jpeg | Ramos | Ramo redondo de rosas | 0.638 |
| 10 | 11.37.17 PM (9).jpeg | Arreglos | Arreglo en caja | 0.424 |
| 11 | 11.37.17 PM (10).jpeg | Ramos | Ramo de mano | 0.529 |
| 12 | 11.37.17 PM (11).jpeg | Ramos | Ramo redondo de rosas | 0.445 |
| 13 | 11.37.17 PM (12).jpeg | Condolencias | Arreglo de condolencia | 0.305 |
| 14 | 11.37.17 PM (13).jpeg | Ramos | Ramo de mano | 0.529 |
| 15 | 11.37.17 PM (14).jpeg | Ramos | Ramo de mano | 0.475 |
| 16 | 11.37.17 PM (15).jpeg | Ramos | Ramo de mano | 0.631 |
| 17 | 11.37.17 PM (16).jpeg | Ramos | Ramo de mano | 0.355 |
| 18 | 11.37.17 PM (17).jpeg | Ramos | Ramo de mano | 0.361 |
| 19 | 11.37.17 PM (18).jpeg | Ramos | Ramo de mano | 0.316 |
| 20 | 11.37.17 PM (19).jpeg | Arreglos | Arreglo en caja | 0.295 |
| 21 | 11.37.17 PM (20).jpeg | Condolencias | Arreglo de condolencia | 0.392 |
| 22 | 11.37.17 PM (21).jpeg | Ramos | Ramo de mano | 0.555 |
| 23 | 11.37.17 PM (22).jpeg | Arreglos | Arreglo en caja | 0.338 |
| 24 | 11.37.17 PM (23).jpeg | Ramos | Ramo de mano | 0.273 |
| 25 | 11.37.17 PM (24).jpeg | Condolencias | Arreglo de condolencia | 0.373 |
| 26 | 11.37.17 PM (25).jpeg | Arreglos | Arreglo en caja | 0.310 |
| 27 | 11.37.17 PM (26).jpeg | Ramos | Ramo de mano | 0.489 |
| 28 | 11.37.18 PM.jpeg | Ramos | Ramo de mano | 0.401 |
| 29 | 11.37.18 PM (1).jpeg | Ramos | Ramo redondo de rosas | 0.375 |
| 30 | 11.37.18 PM (2).jpeg | Arreglos | Arreglo en caja | 0.444 |
| 31 | 11.37.18 PM (3).jpeg | Arreglos | Arreglo en caja | 0.445 |
| 32 | 11.37.18 PM (4).jpeg | Arreglos | Arreglo en caja | 0.247 |
| 33 | 11.37.18 PM (5).jpeg | Arreglos | Arreglo en caja | 0.375 |
| 34 | 11.37.18 PM (6).jpeg | Ramos | Ramo de mano | 0.557 |

## Casos que conviene revisar

En una primera pasada del modelo, estas fotos fueron clasificadas de forma distinta, así que son las más dudosas:

- **11** y **22**: primero como arreglo en caja, después como ramo de mano.
- **13** y **21**: primero como arreglo en caja, después como condolencia.
- **24**: primero como arreglo en caja, después como ramo de mano.
- **32**: confianza baja (0.247) entre arreglo en caja y ramo redondo.
- **20**: confianza baja (0.295) entre arreglo en caja y ramo de mano.

También hay varias fotos con confianza entre 0.30 y 0.40 donde el modelo dudó entre “ramo de mano envuelto” y “arreglo en caja”. Si me dices cuáles son, ajusto la galería en un momento.
