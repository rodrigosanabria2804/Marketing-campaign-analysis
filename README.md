# Análisis de Performance y Segmentación: Optimización de Conversión en Marketing
*Por Rodrigo Sanabria Chavarria*

## 1. Contexto del Proyecto
Este análisis se centra en evaluar la efectividad de las campañas de marketing digital mediante el estudio de las tasas de conversión y retención. El objetivo es identificar qué segmentos de usuarios (por idioma y canal) responden mejor a los anuncios personalizados para optimizar la asignación del presupuesto de marketing.

## 2. Definición del Problema (Business Case)
La empresa necesita entender si la personalización del idioma en los anuncios genera un "lift" (incremento) real en la conversión o si los resultados actuales son fruto del azar.
**Preguntas clave:**
* ¿Cuál es nuestra tasa de conversión base?
* ¿Qué canales (Facebook, Instagram, Email, etc.) retienen mejor a los usuarios?
* ¿Es rentable invertir en traducción de anuncios para mercados específicos (Árabe, Alemán, Español)?

## 3. Stack Tecnológico
* **Python** (Procesamiento y limpieza)
* **Pandas / Numpy** (Manipulación de series temporales y segmentación)
* **Matplotlib** (Visualización de tendencias diarias)
* **Scipy (Stats)** (Pruebas de significancia estadística / P-values)

## 4. Hallazgos Principales (Insights)
A partir del análisis del notebook, se identificaron los siguientes puntos críticos:

* **Tasa de Conversión General:** 13.89%
* **Tasa de Retención:** 66.8% (Punto de optimización identificado).
* **Efecto del Idioma:** * El segmento **Español** mostró el mayor crecimiento con un **Lift del 166.67%** (p = 0.04), demostrando que la personalización es crítica en este mercado.
    * El mercado **Inglés** tuvo un lift sólido del 39% (p = 0.027).
    * En el mercado Árabe, aunque hubo un lift del 50%, no fue estadísticamente significativo (p = 0.58).

## 5. Estructura del Repositorio
* `Marketing Analysis.ipynb`: Notebook principal con el flujo de limpieza, EDA y pruebas estadísticas.
* `marketing.csv`: Dataset con logs de usuarios y resultados de conversión.
* `visuals/`: Capturas de los gráficos de tendencias de usuarios diarios.

## 6. Conclusiones y Recomendaciones de Marketing
1. **Priorización de Inversión:** Escalar la personalización de anuncios en español de inmediato, dado su alto impacto y significancia.
2. **Revisión de Campañas en Árabe:** No invertir más en traducciones para este segmento hasta recolectar más datos, ya que el impacto actual no es concluyente.
3. **Foco en Retención:** Con una retención del 66%, se recomienda implementar una campaña de "re-engagement" específicamente en los canales con menor desempeño para elevar el LTV (Lifetime Value).

---
*Este proyecto forma parte de mi portafolio como Marketing Manager especializado en Business Analytics.*
