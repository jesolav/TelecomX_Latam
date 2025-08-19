# 📊 Telecom X LATAM - Predicción de Cancelación (Churn)

Este repositorio contiene el desarrollo del desafío **Telecom X: Predicción de Cancelación (Churn)**.

## 🚀 Objetivos
- Aplicar ETL con Python para preparar los datos de clientes de Telecom X.
- Desarrollar modelos de clasificación para predecir la cancelación de clientes (**Churn**).
- Evaluar los modelos mediante métricas de desempeño.
- Identificar los factores principales que influyen en la cancelación.

## 📂 Estructura del proyecto
- `TelecomX_Data.json`: Datos crudos en formato JSON.
- `TelecomX_diccionario.md`: Diccionario de variables.
- `TelecomX_LATAM.ipynb`: Notebook principal con el desarrollo completo.
- `README.md`: Descripción del proyecto.

## 🧰 Librerías utilizadas
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

## 📌 Flujo de trabajo
1. **Extracción**: Carga de datos desde JSON.
2. **Transformación**: Limpieza, imputación de valores faltantes, codificación y escalado.
3. **Carga y análisis**: EDA y construcción de modelos predictivos.
4. **Informe Final**: Conclusiones estratégicas y recomendaciones de negocio.

## 🤖 Modelos aplicados
- **Regresión Logística**
- **Random Forest**

## 📈 Principales insights
- Los clientes con **contratos mensuales** presentan mayor probabilidad de cancelación.
- Pagos con **Electronic Check** se asocian con mayor churn.
- La **antigüedad (tenure)** es clave: clientes nuevos (<12 meses) tienen mayor tasa de churn.
- Los usuarios de **Fiber Optic sin servicios adicionales** presentan alto riesgo.
