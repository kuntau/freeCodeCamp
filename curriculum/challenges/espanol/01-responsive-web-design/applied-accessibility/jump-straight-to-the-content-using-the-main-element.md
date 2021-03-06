---
id: 587d774e367417b2b2512a9f
title: Salta directamente al contenido usando el elemento principal (main)
challengeType: 0
videoUrl: 'https://scrimba.com/c/cPp7zuE'
forumTopicId: 301018
dashedName: jump-straight-to-the-content-using-the-main-element
---

# --description--

HTML5 introdujo una serie de nuevos elementos que ofrecen a los desarrolladores más opciones al tiempo que incorporan características de accesibilidad. Estas etiquetas incluyen `main`, `header`, `footer`, `nav`, `article`, y `section`, entre otros.

Por defecto, un navegador representa estos elementos de manera similar a la humilde `div`. Sin embargo, usarlos cuando sea apropiado da un significado adicional en tu lenguaje de marcado. El nombre de la etiqueta solo puede indicar el tipo de información que contiene, lo que agrega significado semántico a ese contenido. Las tecnologías de asistencia pueden acceder a esta información para proporcionar mejores opciones de resumen de páginas o de navegación a sus usuarios.

El elemento `main` se usa para envolver (lo adivinaste) el contenido principal, y solo debe haber uno por página. Está destinado a rodear la información que está relacionada con el tema central de su página. No está destinado a incluir elementos que se repiten en todas las páginas, como enlaces de navegación o banners.

La etiqueta `main` también tiene una característica de referencia insertada que la tecnología de asistencia puede usar para navegar rápidamente al contenido principal. Si alguna vez has visto un enlace "Salta al contenido principal" en la parte superior de una página, usando una etiqueta principal proporciona automáticamente a los dispositivos de asistencia esa funcionalidad.

# --instructions--

Camper Cat tiene algunas grandes ideas para su página de armas ninja. Ayúdelo a configurar su marcado agregado etiquetas de apertura y cierre `main` entre el `header` y el `footer` (cubierto en otros desafíos). Mantenga las etiquetas `main` vacías por ahora.

# --hints--

Tu código debe tener una etiqueta `main`.

```js
assert($('main').length == 1);
```

Las etiquetas `main` deben estar entre la etiqueta `header` de cierre y la etiqueta `footer` de apertura.

```js
assert(code.match(/<\/header>\s*?<main>\s*?<\/main>/gi));
```

# --seed--

## --seed-contents--

```html
<header>
  <h1>Weapons of the Ninja</h1>
</header>



<footer></footer>
```

# --solutions--

```html
<header>
  <h1>Weapons of the Ninja</h1>
</header>
<main>

</main>
<footer></footer>
```
