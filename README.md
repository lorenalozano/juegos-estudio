# Juegos de estudio

Web: https://lorenalozano.github.io/juegos-estudio/

Juegos interactivos para repasar, organizados por **curso → asignatura**.

```
index.html                  Portada: elegir curso
estilos.css                 Estilos comunes de todos los menús
404.html                    Página de error; redirige los enlaces antiguos
6-primaria/
  index.html                Menú de asignaturas de 6º
  lengua/                   lengua-tema2-quest.html
  ciencias-naturales/       cuerpo-quest.html
1-eso/
  index.html                Menú de asignaturas de 1º ESO
  biologia-geologia/        geosphere, mineral, rocks, elements
  lengua/                   tildes-quest.html
  ingles/                   verb-quest.html
```

## Añadir un juego

1. Guardar el `.html` en `curso/asignatura/` (crear la carpeta si es nueva).
2. Añadir su tarjeta en el `index.html` de esa asignatura.
3. Actualizar el recuento de juegos en el `index.html` del curso y en la portada.
4. Si es una asignatura o un curso nuevo, copiar un `index.html` vecino como plantilla.

Cada juego es un único archivo HTML que debe empezar por `<!DOCTYPE html>` y llevar `<meta charset="utf-8">`.
