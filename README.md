# Análisis de Evasión de clientes: Caso TelecomX

Este proyecto presenta un análisis detallado sobre la fuga de clientes (Churn) en la empresa TelecomX, con el objetivo de identificar patrones predictivos que permitan mejorar las estrategias de retención.

## 📋 Resumen del Proyecto
El análisis aborda el proceso completo de ciencia de datos, desde la extracción y limpieza de información semiestructurada hasta la identificación de factores clave de abandono, como la antigüedad del usuario, tipos de contrato y métodos de pago.

## 🛠️ Herramientas Utilizadas
El análisis se desarrolló en Python utilizando las siguientes librerías:
* **Pandas & Numpy**: Para la manipulación y transformación de datos.
* **Seaborn & Matplotlib**: Para la generación de visualizaciones estadísticas.

## 📊 Hallazgos Principales
* **Tasa de Abandono**: Se identificó una tasa de churn del **26.5%**, lo que representa que aproximadamente 1 de cada 4 clientes cancela el servicio.
* **Perfil de Riesgo**: Los clientes adultos mayores (>= 65 años) y aquellos sin pareja o dependientes muestran una mayor propensión al abandono.
* **Factores Contractuales**: El tipo de contrato y los cargos mensuales son variables críticas en la decisión de permanencia.

## ⚙️ Proceso Técnico
1. **Extracción**: Carga de datos desde repositorio externo en formato JSON[cite: 6, 7].
2. **Transformación**: Normalización de estructuras anidadas y limpieza de 7,267 registros[cite: 9, 13].
3. **Métricas**: Creación de la métrica `CuentasDiarias` para analizar el gasto prorrateado por cliente[cite: 50, 54].
4. **Análisis (EDA)**: Inspección de variables binarias, categóricas y numéricas para detectar inconsistencias y patrones[cite: 29, 55].

## 🚀 Cómo ejecutar
1. Clona el repositorio.
2. Asegúrate de tener instaladas las dependencias: `pip install pandas numpy seaborn matplotlib`.
3. Ejecuta el notebook `TelecomX_LATAM.ipynb` para reproducir el análisis.
