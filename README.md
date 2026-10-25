# Bioinformática Reproducible

Repositorio de ejercicios prácticos de la Unidad 1, Sesión 1.

## Ejercicio 1: extracción de identificadores de maíz

El archivo `nombres_maiz.txt` contiene los identificadores extraídos de la segunda columna del archivo de muestras mediante `awk`.

## Ejercicio 2: creación de directorios de poblaciones

El script `crear_poblaciones.sh` crea los directorios `PobA`, `PobB`, `PobC` y `PobD`, y genera un archivo `individuo.txt` en cada uno.

Para ejecutarlo desde esta carpeta:

    bash crear_poblaciones.sh

## Ejercicio 3: conteo de TGCA en secuencias matK

El script `ejercicio3/contar_tgca.sh` cuenta las apariciones de `TGCA` en registros FASTA.

Los datos de entrada están en `ejercicio3/secuencias_matk.fasta` y los resultados en `ejercicio3/resultados_tgca.txt`.

Para ejecutar el análisis:

    cd ejercicio3
    bash contar_tgca.sh

## Reproducibilidad

Los scripts, datos de entrada seleccionados y resultados permiten revisar los procedimientos realizados durante los ejercicios.
