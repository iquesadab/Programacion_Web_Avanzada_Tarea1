# Tarea 1 - Programación Web Avanzada

## Identificación

**Estudiante:** Ivannia Vanessa Quesada Bogantes  
**Curso:** Programación Web Avanzada  
**Sección:** SCV2  
**Docente:** Álvaro Cordero Peña  
**Fecha de entrega:** 20 de septiembre de 2026  

## Descripción

Esta tarea consiste en el desarrollo de dos interfaces web adaptables utilizando HTML5 y CSS3.

### Caso 1 - Centro de control de una expedición científica

Interfaz para visualizar el estado general de una expedición científica, incluyendo misiones, equipos, alertas y próximas actividades.

### Caso 2 - Panel público de información de un festival

Interfaz para que los asistentes de un festival puedan consultar las actividades actuales y próximas, los diferentes escenarios, cambios importantes y servicios disponibles.

## Estructura del repositorio

Tarea1/
├── README.md  
├── caso1/  
│   ├── index.html  
│   ├── css/  
│   │   └── estilos.css  
│   └── img/  
└── caso2/  
    ├── index.html  
    ├── css/  
    │   └── estilos.css  
    └── img/  

## Instrucciones para abrir los casos

### Caso 1

1. Abrir la carpeta `caso1`.
2. Abrir el archivo `index.html` en un navegador web.

### Caso 2

1. Abrir la carpeta `caso2`.
2. Abrir el archivo `index.html` en un navegador web.

## Decisiones de diseño

● Por qué seleccionó determinadas etiquetas semánticas.
Se utilizaron etiquetas como header, nav, main, section, article, aside y footer para organizar el contenido según la función que cumple cada parte de la página.

● Cómo organizó la jerarquía de encabezados.  
Se utilizó h1 para el título principal de cada caso, h2 para las secciones principales y h3 para los títulos de tarjetas, actividades, misiones o escenarios.

● Cómo incorporó la accesibilidad básica.  
Se definió el idioma con lang="es", se mantuvo una jerarquía ordenada de encabezados, se utilizaron textos claros y los estados no dependen únicamente del color, ya que también se identifican mediante texto e íconos.

● Cómo funciona el modelo de caja en sus principales componentes.  
Se utilizó box-sizing: border-box para que el padding y los bordes formen parte del tamaño de los elementos. Las tarjetas utilizan padding, bordes y márgenes para separar y organizar su contenido.

● Dónde utilizó posicionamiento, cuál valor de position empleó y por qué.  
Se utilizó position: sticky en la navegación para mantenerla visible al desplazarse por la página. En el Caso 2 también se utilizó relative y absolute para colocar la etiqueta “En este momento” dentro de las tarjetas de actividades actuales.

● Por qué algunos estilos prevalecen sobre otros.  
Los estilos base están pensados para teléfono y posteriormente las media queries modifican algunas propiedades para tableta y escritorio. También se utilizaron selectores más específicos cuando fue necesario aplicar estilos a elementos particulares.

● Dónde utilizó Flexbox y por qué.  
Se utilizó Flexbox principalmente en la navegación y dentro de algunos componentes, como indicadores, actividades y servicios, porque facilita alinear elementos en una sola dirección y controlar el espacio entre ellos.

● Dónde utilizó CSS Grid y por qué.  
Se utilizó Grid para organizar la estructura principal de ambos casos y las tarjetas de secciones como resumen, misiones, equipos, programación y servicios. Grid permitió cambiar fácilmente la cantidad y distribución de columnas según el tamaño de pantalla.

● Cómo cambia el layout entre teléfono, tableta y escritorio.  
En teléfono se prioriza una distribución principalmente vertical. En tableta se comienzan a utilizar dos o más columnas y en escritorio se aprovecha más el ancho para mostrar varias zonas de información simultáneamente.

● Cuáles media queries utilizó y por qué seleccionó esos breakpoints.  
Se utilizaron 48rem para tableta y 64rem para escritorio. Estos puntos permiten reorganizar el contenido cuando existe suficiente espacio, manteniendo primero el diseño para teléfono.

● Cuáles unidades relativas utilizó.  
Se utilizaron principalmente rem para tamaños, espacios y breakpoints, y fr en CSS Grid para distribuir proporcionalmente el espacio disponible.

● Para qué sirven las variables CSS que definió.  
Las variables definidas en :root permiten reutilizar colores, espaciados y tamaños de bordes. Esto ayuda a mantener un diseño consistente y facilita realizar cambios sin modificar cada regla por separado.

## Resumen de commits

| # | Fecha | Hash | Mensaje | Caso | Cambio |
|---|---|---|---|---|---|
| 1 | 2026-09-15 | bbbd506 | Initial commit | Ambos | Inicialización del repositorio
| 2 | 2026-09-15 | b166159 | [new]: Agrega estructura inicial del README | Ambos | Estructura inicial de documentación
| 3 | 2026-09-15 | 74ad669 | [new]: Completa estructura HTML y estilos base del Caso 1 | Caso 1 | Estructura HTML y estilos iniciales |
| 4 | 2026-09-18 | c3e6670 | [improve]: Aplica Grid y Flexbox al diseño responsive del Caso 1 | Caso 1 | Implementación de Grid y Flexbox |
| 5 | 2026-09-20 | 6748088 | [improve]: Finaliza diseño responsive del Case 1 | Caso 1 | Adaptación para teléfono, tableta y escritorio |
| 6 | 2026-09-20 | aab6a91 | [new]: Implementa diseño responsive del Case 2 | Caso 2 | Desarrollo del panel responsive del festival |
| 7 | | 2026-09-20 | 1228234 | [docs]: Completa documentación final del README | Ambos | Finalización de README