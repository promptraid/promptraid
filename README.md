# PromptRaid

Sitio de PromptRaid: juegos hechos con IA y el prompt de regalo.

Es un sitio estático, sin build: `index.html` en la raíz, imágenes en `img/`, juegos en `juegos/` y prompts en `prompts/`.

## Agregar un juego nuevo

1. Copiá el HTML del juego en `juegos/` (un solo archivo).
2. Copiá el prompt en `prompts/` como `.txt`.
3. Sumá una tarjeta en la sección `#juegos` de `index.html`.

## Publicación

Render (sitio estático): sin comando de build, carpeta publicada `.` (la raíz). Cada push a `main` se publica solo.
