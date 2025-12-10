# Sticky Nav – JavaScript30 Challenge

## Descripción General
Este proyecto corresponde al reto "Sticky Nav" del curso JavaScript30. El objetivo es implementar una barra de navegación que permanece fija en la parte superior de la página al realizar scroll, mejorando la experiencia de lectura y la usabilidad.  
El desarrollo se realizó utilizando únicamente HTML, CSS y JavaScript, sin frameworks externos.

## Objetivo del Reto
Replicar el comportamiento del menú fijo mediante manipulación del DOM y eventos de desplazamiento. Se buscó comprender el funcionamiento del position: fixed, el cálculo dinámico de distancias y el ajuste del contenido al fijar la barra de navegación.

## Tecnologías Utilizadas
- HTML5  
- CSS3  
- JavaScript (Vanilla)  
- Git y GitHub para control de versiones  
- GitHub Pages para despliegue del proyecto  

## Funcionamiento
- La barra de navegación se detecta mediante `offsetTop` para conocer su posición inicial.
- Cuando el usuario realiza scroll y supera dicha posición, se activa una clase que fija el menú en la parte superior.
- El contenido principal aplica un `padding-top` dinámico para evitar saltos visuales al fijar la navegación.
- Todo el comportamiento se gestiona a través del evento `scroll`.

## Estructura del Proyecto
Despliegue

El proyecto se encuentra disponible de forma pública en GitHub Pages:
https://jjjosueva.github.io/RetoJosue/

Autor

Josue Valencia
Proyecto realizado como parte del curso JavaScript30 y práctica académica de desarrollo web.
