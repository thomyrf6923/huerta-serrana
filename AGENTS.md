# Reglas del proyecto Huerta Serrana

Estas reglas se aplican a todas las páginas y archivos del proyecto.

## Tecnología y funcionamiento

- Usar solo HTML5 semántico y CSS3 puro.
- No usar JavaScript ni frameworks CSS, incluidos Bootstrap y Tailwind.
- No cargar recursos externos en tiempo de ejecución: CDNs, Google Fonts, analíticas u otros servicios. El sitio debe funcionar sin conexión a internet.
- Usar fuentes del sistema: `system-ui` y `Georgia`.

## CSS y sistema de diseño

- Aplicar BEM estricto a las clases: `.bloque__elemento--modificador`.
- No usar atributos `style`, declaraciones `!important` ni selectores de ID (`#id`) para estilos.
- Definir los valores del sistema de diseño exclusivamente en `css/tokens.css` y consumirlos mediante variables CSS.
- No usar colores hexadecimales sueltos ni tamaños de fuente en `px`; usar `rem` para los tamaños de fuente.

## Contenido

- Usar exclusivamente los datos de los cinco CSV de `data/` (Anexo B) para el contenido factual.
- No inventar precios, productos, certificaciones ni testimonios.

## Accesibilidad

- Incluir exactamente un `<h1>` por página y mantener una jerarquía de encabezados sin saltos de nivel.
- Incluir `alt`, `width` y `height` en todas las imágenes.
- Asociar cada campo de formulario con un `<label for="...">`.
- Mantener un indicador de foco visible para los elementos interactivos.
- Implementar el menú móvil plegable sin JavaScript, mediante `<details>` y `<summary>`.
