# Informe preliminar: Biomasa y emisiones de CO₂ en España

## Introducción
Este estudio analiza la evolución del consumo de biomasa en España y su posible relación con la reducción de emisiones de CO₂, utilizando datos abiertos (fuentes: Our World in Data, Eurostat).

## Datos
- `data/co2_emisiones_espana.csv` → emisiones históricas de CO₂ (1990–2023).
- `data/biomasa_consumo_espana.csv` → consumo de biomasa en Mtep (1990–2023).

## Resultados
A continuación se muestra la evolución conjunta:

![Evolución de emisiones y biomasa](report_fig_01.png)

Se observa que:
- El consumo de biomasa crece de manera continua.
- Las emisiones de CO₂ alcanzan un máximo hacia mediados de los 2000 y luego descienden.
- Existe una correlación inversa: a medida que aumenta la biomasa, las emisiones tienden a reducirse.

## Próximos pasos
- Calcular coeficientes de correlación.
- Incluir análisis por sectores.
- Añadir más años y fuentes de datos para robustecer las conclusiones.
