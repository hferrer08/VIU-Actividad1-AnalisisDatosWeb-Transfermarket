# Actividad 1 - Análisis de Datos Web

## Descripción

Este proyecto corresponde a la Actividad 1 de la asignatura **Análisis de Datos Web** del Máster Universitario de la **Universidad Internacional de Valencia (VIU)**.

El objetivo de la actividad consiste en realizar un proceso de exploración, limpieza, transformación y preparación de datos utilizando Python y Pandas en Google Colab, para posteriormente construir un dashboard interactivo mediante Power BI.

Para el desarrollo del trabajo se utilizó un conjunto de datos públicos de **Transfermarkt**, que contiene información relacionada con jugadores, clubes y competiciones de fútbol profesional.

---

## Dataset utilizado

**Fuente:** Transfermarkt (Kaggle)

El conjunto de datos incluye información sobre:

- Jugadores de fútbol.
- Clubes profesionales.
- Competiciones nacionales e internacionales.
- Valoraciones históricas de mercado.

### Archivos utilizados

- `players.csv`
- `clubs.csv`
- `competitions.csv`
- `player_valuations.csv`

---

## Objetivos del análisis

- Explorar la estructura y calidad de los datos.
- Identificar valores nulos y registros duplicados.
- Analizar las relaciones existentes entre las diferentes tablas.
- Preparar un conjunto de datos consolidado para análisis.
- Generar visualizaciones e indicadores mediante Power BI.

---

## Tecnologías utilizadas

- Python 3
- Pandas
- Google Colab
- Power BI Desktop
- GitHub

---

## Proceso realizado

### 1. Carga de datos

Se cargaron los archivos CSV originales mediante Google Colab utilizando la librería Pandas.

### 2. Exploración inicial

Se revisó:

- Cantidad de registros.
- Cantidad de columnas.
- Tipos de datos.
- Estructura de cada tabla.

### 3. Limpieza de datos

Se identificaron:

- Valores nulos.
- Posibles inconsistencias.
- Registros duplicados.

No se detectaron registros duplicados en las tablas analizadas.

### 4. Transformación de datos

Se seleccionaron únicamente las columnas relevantes para el análisis.

Posteriormente se integró la información de jugadores, clubes y competiciones mediante operaciones de unión (JOIN) utilizando Pandas.

### 5. Creación del dataset analítico

Se generó un conjunto de datos consolidado denominado:

`dashboard_transfermarkt.csv`

Este archivo contiene la información necesaria para construir el dashboard final en Power BI.

---

## Estructura del repositorio

```text
.
├── Cleaning_data.ipynb
├── dashboard_transfermarkt.csv
├── Dashboard.pbix
├── Resumen.pdf
└── README.md
```

---

## Resultados esperados

El dashboard desarrollado en Power BI permite analizar:

- Valor de mercado de jugadores.
- Distribución por posiciones.
- Información de clubes.
- Información de competiciones.
- Distribución geográfica de jugadores.
- Indicadores generales del mercado futbolístico.

---

## Autor

**Hubert Ferrer Guerrero**

Máster Universitario en Desarrollo de Aplicaciones y Servicios Web

Universidad Internacional de Valencia (VIU)