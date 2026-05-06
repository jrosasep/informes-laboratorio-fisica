# Informes de laboratorio — Física UdeC

Este repositorio reúne informes experimentales desarrollados durante cursos de laboratorio de la carrera de **Ciencias Físicas** en la **Universidad de Concepción**.

La carpeta está organizada en dos bloques principales:

- `laboratorio2/`: informes del curso **Laboratorio II**.
- `introducción-mecanica-cuantica/`: informes asociados al curso **Introducción a la Mecánica Cuántica**.

Cada informe incluye, según corresponda, el archivo fuente en LaTeX, el PDF compilado, figuras, fotografías del montaje experimental, bibliografía y scripts de análisis en Python usados para procesar datos y generar gráficos.

## Contenido

### Laboratorio II

- **Informe 1:** Ondas estacionarias.
- **Informe 2:** Ley de Ohm.
- **Informe 3:** Índice de refracción y ley de Snell.
- **Informe 4:** Intercambio de energía mecánica en un sistema cuerpo--resorte oscilando.
- **Informe 5:** Calorimetría.
- **Informe 6:** Torque y momento de inercia.

### Introducción a la Mecánica Cuántica

- **Informe 1:** Difracción de la luz.
- **Informe 2:** Medición de la constante de Planck mediante LEDs.
- **Informe 3:** Efecto fotoeléctrico.

## Estructura general

La mayoría de los informes siguen una estructura similar:

```text
informe-x/
├── analisis/        # scripts de Python para procesar datos y generar gráficos
├── figures/         # figuras, gráficos o esquemas usados en el informe
├── images/          # fotografías o material experimental
├── informe-x.tex    # fuente principal en LaTeX
├── informe-x.pdf    # versión compilada del informe
└── references.bib   # bibliografía, cuando corresponde
```

Algunos nombres de carpetas pueden variar ligeramente según el informe, pero la idea general es mantener juntos el texto, los datos procesados, las figuras y el código que permite reproducir el análisis.

## Reproducibilidad

Los scripts de análisis están escritos principalmente en **Python**, usando bibliotecas como `numpy`, `pandas` y `matplotlib`. En general, cada script busca dejar explícito cómo se procesaron los datos experimentales y cómo se generaron los gráficos incluidos en los informes.

Para ejecutar un análisis particular, basta con entrar a la carpeta `analisis/` del informe correspondiente y correr el script asociado, por ejemplo:

```bash
python analisis-torque-momento-inercia.py
```

## Agradecimientos

Estos informes fueron desarrollados en contexto de trabajo experimental y colaborativo para las asignaturas de pregrado mencionadas. Agradezco especialmente a quienes aparecen como compañeros de trabajo en los informes: **Fabián Contreras Muñoz**, **Javier Chandia Valdés**, **Mario Díaz San Martín**, **Martin Fierro Sagredo** y **N. Ulloa C.**

También se agradece al profesor **Paulraj Manidurai** por la guía docente en las experiencias de laboratorio.

## Nota

Estos informes fueron elaborados como material académico de curso. Pueden contener decisiones experimentales, aproximaciones y errores propios del trabajo de laboratorio, por lo que deben leerse como registros de aprendizaje y análisis físico, no como documentos cerrados o definitivos.
