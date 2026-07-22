# Proyecto SASS - Mixins y Extend


## Descripción

En este proyecto se aplicaron conceptos avanzados de SASS como mixins parametrizados, directiva @extend, placeholders y condicionales.

El objetivo fue mejorar la organización del código CSS aplicando el principio DRY (Don't Repeat Yourself), evitando repetir estilos y creando componentes reutilizables.


## Implementaciones realizadas


### Mixins

Se crearon mixins para botones reutilizando estilos comunes y permitiendo modificar valores como color y padding mediante parámetros.


### Parámetros

Se utilizaron parámetros posicionales y valores por defecto para generar componentes flexibles.


### @content

Se implementó un mixin para contenedores flexibles permitiendo agregar reglas CSS adicionales desde el selector.


### @extend

Se utilizó @extend mediante placeholders (%) para compartir estilos entre tarjetas evitando duplicación de código.


### Condicionales

Se aplicaron estructuras @if y @else dentro de mixins para generar diferentes variantes de botones.


## Conclusión

Los mixins resultan adecuados para componentes que necesitan variaciones mediante parámetros, mientras que @extend es útil cuando existe una relación semántica clara entre elementos.

Se evitó abusar de @extend para prevenir combinaciones inesperadas en el CSS generado.