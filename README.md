![What-is-data-science-2](https://github.com/user-attachments/assets/7a51a034-1890-4d5d-8fc9-13e528117c59)
🔮 Predicción de Ventas con ARIMA | Análisis de Series Temporales para Cencosud

Este proyecto aplica técnicas avanzadas de análisis de series temporales con Python para pronosticar las ventas de la empresa Cencosud, uno de los principales retailers de América Latina. A través del modelamiento estadístico con ARIMA, se genera un modelo robusto capaz de anticipar el comportamiento futuro del negocio.

📌 Descripción del proceso realizado:

1. Carga y exploración de datos:
Se parte de un dataset histórico de ventas, que es analizado para comprender su estructura temporal y evaluar posibles transformaciones.

2. Preprocesamiento:

   - Conversión de fechas a formato de índice temporal

   - Agrupación por periodos mensuales

   - Visualización de tendencias y estacionalidades

   - Revisión de valores atípicos o inconsistencias

3. Análisis de Estacionariedad:
Se aplican pruebas estadísticas (como ADF) y visualizaciones (rolling mean y std) para evaluar la estacionariedad, condición clave para aplicar modelos ARIMA.

4. Modelado con ARIMA:

  - Identificación de parámetros óptimos (p, d, q) mediante el análisis ACF y PACF

  - Entrenamiento del modelo ARIMA con statsmodels

  - Evaluación del ajuste y diagnóstico de residuos

5. Pronóstico y Visualización:
Se realizan predicciones a futuro y se representan gráficamente junto a los datos históricos para facilitar la interpretación del modelo y validar su precisión.

📊 Resultado:
Un modelo ARIMA ajustado que permite proyectar el comportamiento mensual de las ventas de Cencosud, útil para respaldar decisiones estratégicas de inventario, compras y logística.

💡 Tecnologías usadas:
Python · Pandas · Matplotlib · Statsmodels · ARIMA · Series temporales
