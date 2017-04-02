# Front end Core

Core con los archivos necesarios para comenzar un proyecto de front end.

## Iniciando un proyecto

1.  Crear un directorio www y clonar dentro el repositorio desde gitlab.
2.  Abrir el archivo bower.json y cambiar el nombre del proyecto por el nuevo que se desarrollará.
3.  Agregar solo el directorio html a Prepros y cambiar el nombre del proyecto por el nuevo que se desarrollará.
4.  Crear un proyecto nuevo en SublimeText / ATOM

## Configuracion global de Prepros
Ir a Project Settings -> Compiler Setting

### CSS / SASS Compilers
*  ✓ Auto Compile
*  ✓ Source Map
*  Process With: Node Sass
*  Node Sass: Expanded
*  ✓ Autoprefixer
*  Output Type: Replace Segment
*  Replace Segment: sass / scss
*  Replace Segment With: css

### HTML / PUG Compilers
*  ✓ Auto Compile
*  ✓ Pretty
*  Output Type: Replace to Source
*  Relative: ../../

### Javascript
*  Process With: Concat Js
*  ✓ Concat Js
*  ✓ Uglify Js
*  ✓ Mangle
*  Output Type: Replace to Source
*  Output Suffix: -min

<div style="padding-top:20px">Luego minificamos archivos css y js:</div>

<pre><code>Ir a Files: /css/main.css --> /css/min/main-min.css</code></pre>

<pre><code>Ir a Files: /js/main.js --> /js/min/main-min.js</code></pre>
<pre><code>Ir a Files: /js/recursos.js --> /js/min/recursos-min.js</code></pre>

Más información sobre [Prepros](https://prepros.io/help/getting-started) y configuración de ambiente frontend.

And here's some code! :+1:
