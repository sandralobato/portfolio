# sandralobato.com

Portfolio de **Sandra Lobato Pardavila**, UX / Product Designer. 🌐 [sandralobato.com](https://sandralobato.com) · 🇬🇧 [English](https://sandralobato.com/en/)

Web estática (HTML, CSS y JS sin compilación) publicada con GitHub Pages. Animaciones con GSAP y Lenis, tipografía Geist.

## Estructura

| Ruta | Contenido |
|---|---|
| `index.html` | Home en español |
| `maiteego.html`, `empleo.html`, `proyectos.html`, `filosofia.html` | Casos y páginas en español |
| `en/` | Las mismas páginas en inglés (selector ES / EN arriba a la derecha) |
| `img/` | Imágenes; `img/en/` las láminas traducidas |
| `cv-sandra-lobato-2026*.pdf` | CV en PDF (español e inglés) |
| `CNAME`, `.nojekyll` | Dominio propio y publicación sin Jekyll |

Las láminas del caso de búsqueda de empleo y de las herramientas internas son reconstrucciones con datos ficticios, por confidencialidad.

## ⚠ Mantener sincronizado

Esta web, el CV (PDF y Word) y el perfil [github.com/sandralobato](https://github.com/sandralobato) cuentan lo mismo. **Si actualizas uno, actualiza los otros**: cifras, cargos, fechas y contacto.

Este repositorio es la salida generada, no se edita a mano:

1. Edita las páginas fuente y, para el inglés, sus traducciones.
2. Regenera la versión en inglés y el CV (`scripts/i18n/build.py`, `scripts/cv/build_cv.py`).
3. Regenera esta carpeta con `scripts/build_publicar.py sandralobato.com`, haz commit y push.
