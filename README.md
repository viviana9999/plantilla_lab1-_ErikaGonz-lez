# Laboratorio 1 · Fundación Altiplano

Repositorio de trabajo para el **Laboratorio 1 — Organización en estado Inicial**
de la Escalera de Madurez de Datos.

## Qué hay aquí

```
altiplano.Rproj            Proyecto de RStudio (ábrelo primero)
datos/nivel1/              Datos CRUDOS — no los modifiques nunca
lab_n1_estudiante.qmd      Tu laboratorio: aquí trabajas
salidas/                   Se crea sola al ejecutar; no se versiona
.gitignore                 Qué NO sube al repositorio (léelo: tiene una lección)
```

## Cómo empezar

1. Abre `altiplano.Rproj`. Esto fija el directorio de trabajo: todas las rutas
   del laboratorio son relativas a él y funcionarán sin que cambies nada.
2. Abre `lab_n1_estudiante.qmd`.
3. Ejecuta los bloques de código en orden, de arriba hacia abajo.
4. Completa cada sección marcada con `# TODO`.
5. Renderiza con el botón **Render** para producir tu informe en HTML.

## La regla que no se negocia

**El archivo de `datos/` no se modifica jamás.** Toda corrección se hace en
código, dentro del `.qmd`. Si la próxima semana llega una versión nueva del
archivo, tu trabajo debe poder repetirse ejecutando el mismo código.

Esa regla no es una manía del docente: es la diferencia entre *arreglar un
archivo* y *gobernar un dato*. Un arreglo manual muere contigo; un arreglo en
código es auditable, repetible y transferible.

## Entrega

Haz `commit` y `push` de:

- `lab_n1_estudiante.qmd` con tus respuestas
- el `.html` renderizado
- tu diccionario de datos y tu plan de gobierno

No subas la carpeta `salidas/` ni archivos temporales: de eso se encarga el
`.gitignore`.

## Si algo se rompe

Antes de escribirme, intenta en este orden: reinicia la sesión de R
(*Session → Restart R*), vuelve a ejecutar desde el primer bloque, y lee el
mensaje de error completo —casi siempre dice exactamente qué pasó—. Si sigue
fallando, escríbeme **pegando el mensaje de error**, no una descripción de él.
