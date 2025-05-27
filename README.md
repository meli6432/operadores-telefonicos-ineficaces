# Identificación y clasificación de operadores ineficaces

Este proyecto analiza el rendimiento de operadores telefónicos en una empresa de telecomunicaciones, con el objetivo de identificar perfiles ineficaces y proponer mejoras.

## Objetivo
Detectar operadores con alto porcentaje de llamadas perdidas y largos tiempos de espera utilizando análisis exploratorio y modelos predictivos.

## Tecnologías y herramientas
- Python (Pandas, Matplotlib, Seaborn)
- Scikit-learn (RandomForest, LogisticRegression)
- Tableau (para visualización final)
- Pruebas estadísticas (Mann-Whitney)

## Lo que se hizo
- Limpieza y análisis de datos históricos de llamadas
- Cálculo de KPIs: `missed_call_rate`, `avg_wait_time`, `outgoing_calls`
- Etiquetado de operadores ineficaces
- Entrenamiento de modelos predictivos
- Visualización de insights clave en Tableau

## Resultados
- Modelo Random Forest con precisión >85%
- Ranking de importancia de variables
- Recomendaciones prácticas para supervisores
