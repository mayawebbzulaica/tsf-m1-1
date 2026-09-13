# [Nombre del equipo] — Proyecto Módulo [N]

Repo de equipo para el proyecto del Módulo [N] del curso de Forecasting de
Series de Tiempo (ITESO).

## Integrantes

- Nombre 1
- Nombre 2
- Nombre 3
- Nombre 4

## Qué incluye este repo

- `_quarto.yml`: configuración compartida (HTML autocontenido, tabla de
  contenido, fix de impresión para objetos `mable`/`fable`/`hilo`).
- `.gitignore`: ignora artefactos de render y de RStudio/Positron. El
  `.html` renderizado **sí se versiona a propósito** — es el entregable.

## Cómo trabajar en este repo

1. Clonen el repo en su máquina.
2. Ábranlo en Positron.
3. Instalen los paquetes que falten con `pak::pak("paquete")`.
4. Trabajen en su(s) archivo(s) `.qmd`.
5. Antes de entregar, rendericen (`quarto render`) y hagan commit del
   `.html` junto con el `.qmd`.

## Referencia del curso

Material y convenciones del curso: <https://pbenavidesh.github.io/narsil>

## Licencia

Ver [`LICENSE`](./LICENSE).
