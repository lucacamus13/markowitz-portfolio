# markowitz-portfolio
.
# Optimización de Portafolio con el Modelo de Markowitz

Este proyecto implementa el modelo de media-varianza de Harry Markowitz para construir portafolios óptimos en función de la rentabilidad esperada y el riesgo (volatilidad). Se construyen fronteras eficientes y se identifican combinaciones óptimas según distintos criterios.

## Objetivo

Optimizar la asignación de activos utilizando datos reales de mercado para:
- Minimizar la volatilidad.
- Maximizar la rentabilidad
- Maximizar el ratio de Sharpe.
- Construir la frontera eficiente de inversión.

## Herramientas

- Python: `pandas`, `numpy`, `matplotlib`, `yfinance`, `scipy.optimize`
- Google Colab
- Datos financieros: precios históricos de activos vía `yfinance`

## Metodología

1. Descarga de precios históricos de activos (ej. AAPL, TSLA, AMZN...).
2. Cálculo de rendimientos diarios y anualizados.
3. Estimación de matriz de covarianzas.
4. Simulación de portafolios aleatorios.
5. Construcción de la frontera eficiente.
6. Optimización por:
   - Máximo Sharpe Ratio.
   - Mínima varianza.
   - Portafolio objetivo.

## Resultados

- Gráfico de la frontera eficiente con portafolios simulados.
- Cálculo del portafolio óptimo según diferentes objetivos.
- Visualización del peso óptimo de cada activo.

![Frontera Eficiente]("![image](https://github.com/user-attachments/assets/e473887d-f3d1-4419-9242-29980abc10fb)
")

## Conclusión

El modelo de Markowitz permite visualizar y comparar múltiples combinaciones riesgo/retorno. Aunque simplificado, este enfoque ayuda a entender cómo se construyen portafolios teóricos óptimos. El análisis puede extenderse incluyendo tasas libres de riesgo, restricciones reales o backtesting dinámico.

## Archivos del Proyecto

- `markowitz_portfolio.ipynb`: Notebook principal con el código y visualizaciones.
- `/images`: Gráficos generados desde el análisis.

