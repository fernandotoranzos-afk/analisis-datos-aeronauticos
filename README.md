# ✈️ Análisis de Datos Aeronáuticos en Argentina

Este proyecto analiza datos de tráfico aéreo en Argentina utilizando Python para identificar patrones en la distribución de pasajeros por provincia y tipo de vuelo (doméstico vs internacional).

---

## 🎯 Objetivo

Transformar y analizar datos operativos de vuelos y aeropuertos para:

- Identificar concentración de pasajeros por provincia
- Comparar vuelos domésticos vs internacionales
- Generar datasets listos para visualización (Power BI)

---

## 🛠️ Tecnologías utilizadas

- Python (Pandas)
- Jupyter Notebook
- Power BI (visualización)
- CSV (fuentes de datos)

---

## 📂 Dataset

Se utilizan dos fuentes principales:

1. **Datos del Ministerio (2020)**
   - Información de vuelos (pasajeros, aerolínea, origen/destino)

2. **Datos de aeropuertos**
   - Ubicación, provincia, tipo y tráfico

---

## 🧹 Proceso de limpieza

- Corrección de encoding (latin1 → utf-8)
- Normalización de nombres de columnas
- Eliminación de caracteres corruptos
- Limpieza de variables categóricas

---

## 🔄 Transformación de datos

- Selección de variables relevantes
- Conversión de fechas y horas
- Creación de variables:
  - `hora`
  - `franja_horaria`

---

## 🔗 Integración de datos

Se realiza un **merge entre vuelos y aeropuertos** utilizando:

- `aeropuerto` (dataset ministerio)
- `local` (dataset aeropuertos)

---

## 📊 Análisis exploratorio

- Estadísticas descriptivas
- Distribución de pasajeros
- Validación de calidad de datos

---

## 📈 Análisis principal

Se construye una tabla dinámica para analizar:

- Pasajeros por provincia
- Diferenciación por tipo de vuelo:
  - Doméstico
  - Internacional

Luego se transforma a formato largo (unpivot) para facilitar visualización.

---

## 📁 Output generado

Este dataset está listo para ser utilizado en herramientas de BI.

---

## 📊 Visualización

El dataset fue utilizado en Power BI para construir dashboards de:

- Distribución de pasajeros por provincia
- Comparación doméstico vs internacional

📸 Ver dashboard:
![Dashboard](captura.png)

---

## 🧠 Conclusiones

- El tráfico aéreo se concentra principalmente en Buenos Aires
- Existe una gran diferencia entre vuelos domésticos e internacionales
- La limpieza de datos fue clave para asegurar consistencia

---

## 🚀 Próximas mejoras

- Automatización del pipeline
- Incorporación de más años de datos
- Análisis temporal (evolución mensual)

---

## 👤 Autor

Fernando Toranzos  
Data Analyst en formación  
Python | SQL | Power BI | Aviation Data

El proyecto genera el archivo:

