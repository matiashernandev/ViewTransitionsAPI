[DOC](https://developer.chrome.com/docs/web-platform/view-transitions/)
[🤯](https://twitter.com/charca/status/1637832314364497920)
# API de transiciones de vista (View Transitions API)

La API de transiciones de vista (View Transitions API) es una herramienta que permite actualizar el DOM en un solo paso mientras se genera una transición animada entre dos estados. Esta característica está disponible en Chrome 111+ y actualmente está en versión beta.

## ¿Por qué necesitamos esta función?

Las transiciones de página no solo se ven geniales, sino que también comunican la dirección del flujo y hacen que quede claro qué elementos están relacionados de página a página. Incluso pueden ocurrir durante la búsqueda de datos, lo que lleva a una percepción más rápida del rendimiento.

Sin embargo, ya tenemos herramientas de animación en la web, como las transiciones CSS, las animaciones CSS y la API Web Animation. Entonces ¿por qué necesitamos algo nuevo para mover cosas? La verdad es que las transiciones entre estados son difíciles incluso con las herramientas que ya tenemos. Incluso algo como un simple cross-fade implica que ambos estados estén presentes al mismo tiempo. Esto presenta desafíos de usabilidad.

Las transiciones de vista te brindan una forma más fácil al permitirte realizar cambios en el DOM sin superposición entre estados y crear una animación de transición entre los estados utilizando vistas instantáneas.

## Estado de estandarización

La función se está desarrollando dentro del Grupo de Trabajo CSS del W3C como una especificación preliminar. Una vez que estemos satisfechos con el diseño del API, comenzaremos los procesos y controles necesarios para enviar esta función a estable.
