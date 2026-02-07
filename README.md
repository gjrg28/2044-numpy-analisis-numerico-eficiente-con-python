# Análisis de Evasión de Clientes (Churn Analysis)

Este proyecto realiza un análisis exploratorio de datos (EDA) detallado para identificar los factores que influyen en la pérdida de clientes (evasión) en una empresa de servicios. El objetivo es proporcionar información estratégica para reducir la tasa de abandono.

## 🚀 Contenido del Proyecto

El análisis se divide en las siguientes etapas clave:

1. **Limpieza y Preparación de Datos:**
   - Manejo de valores nulos y espacios en blanco.
   - Conversión de tipos de datos (Objetos a `int64`).
   - Renombramiento de columnas para mejorar la legibilidad.

2. **Análisis de Variables Categóricas:**
   - Distribución de la evasión según género, tipo de contrato y método de pago.
   - Uso de tablas de contingencia normalizadas para comparar perfiles de clientes.

3. **Análisis de Variables Numéricas:**
   - Comparación de distribuciones de "Cuenta Diaria" y "Tiempo de Contrato" entre clientes que se quedan y los que se van.
   - Identificación de umbrales críticos de precio mediante Boxplots y gráficos KDE.

4. **Análisis de Servicios Contratados:**
   - Estudio de la relación entre la cantidad de servicios adicionales y la lealtad del cliente.
   - Identificación de "servicios ancla" que reducen significativamente la probabilidad de evasión.

## 📊 Visualizaciones Destacadas

En este notebook encontrarás:
- **Gráficos de Barras Apiladas:** Para visualizar proporciones de abandono.
- **Boxplots:** Para analizar el impacto del gasto mensual en la decisión del cliente.
- **Gráficos de Barras Horizontales:** Para comparar el rendimiento de servicios individuales (Seguridad Online, Soporte Técnico, etc.).

## 🛠️ Tecnologías Utilizadas

* [Python](https://www.python.org/)
* [Pandas](https://pandas.pydata.org/) - Manipulación de datos.
* [Seaborn](https://seaborn.pydata.org/) & [Matplotlib](https://matplotlib.org/) - Visualización de datos.
* [Google Colab](https://colab.research.google.com/) - Entorno de desarrollo.

## 📋 Conclusiones Principales (Ejemplo)
* Los clientes con contratos "Mes a Mes" presentan la mayor tasa de evasión.
* La contratación de servicios de **Seguridad Online** y **Soporte Técnico** está correlacionada con una mayor retención.
* Existe un incremento en el abandono cuando los cargos diarios superan la mediana del mercado.

---
*Este análisis fue realizado como parte de una iniciativa de inteligencia de negocios para optimizar la retención de clientes.*
