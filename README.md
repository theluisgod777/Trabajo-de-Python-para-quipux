# Trabajo-de-Python-para-quipux

Este script realiza un análisis completo del conjunto de datos **Heart Disease** del repositorio UCI.  
Incluye los siguientes pasos principales:

1. **Carga de datos:** descarga y estructura el dataset original.  
2. **Limpieza:** elimina valores nulos y registros inválidos, y binariza la variable objetivo.  
3. **Filtrado:** genera subconjuntos específicos (por edad, sexo, presión arterial, colesterol, etc.).  
4. **Estadísticas descriptivas:** calcula medidas como promedio, mediana y desviación estándar.  
5. **Agrupaciones:** organiza los datos por edad, sexo y tipo de dolor de pecho.  
6. **Consolidación:** crea una tabla resumen con tasas de enfermedad y valores promedios.  
7. **Visualizaciones:** genera seis gráficos que muestran la distribución y relaciones entre variables.  
8. **Conclusiones:** resume los factores de riesgo más importantes y recomendaciones preventivas.

# Juego del Dragón 🐉

Este programa es un pequeño juego de consola en Python donde el jugador debe entrenar, recuperar energía y prepararse para enfrentarse a un dragón.  
Durante la partida, el jugador puede realizar diferentes acciones que afectan su nivel, energía, experiencia y vidas.

## Características principales
- **Sistema de vidas** representado con corazones (`♥` y `♡`).
- **Gestión de energía y pociones** para mantener al jugador en forma.
- **Entrenamiento** para ganar experiencia y subir de nivel.
- **Búsqueda de espada** si el jugador aún no la tiene.
- **Sistema de combate** con resultados aleatorios (victoria, derrota o empate).
- **Condiciones dinámicas** para verificar si el jugador está listo para luchar contra el dragón.

## Estructura del juego
1. Muestra el estado actual del jugador.  
2. Permite usar pociones, descansar o entrenar.  
3. Verifica si es posible pelear contra el dragón.  
4. Simula una batalla con resultados aleatorios.  
5. Termina el juego si el jugador pierde todas las vidas.

El análisis fue desarrollado originalmente en Google Colab y puede ejecutarse en el siguiente enlace:  
🔗 [Actividad de Python](https://colab.research.google.com/drive/1PHgTLUXaWP5V0cVU8e5oLeb8yhLVQlYd?usp=sharing)
🔗 [Juego del dragon, actividad de bonificacion](https://colab.research.google.com/drive/1PHgTLUXaWP5V0cVU8e5oLeb8yhLVQlYd?usp=sharing)
https://colab.research.google.com/drive/1fNkilavllOzbyuCinjdQViudd4cN4MG5?authuser=0#scrollTo=TS2uKP10G-3i
---

**Requisitos:**  
- Python 3.8 o superior  
- Librerías: `pandas`, `numpy`, `matplotlib`, `seaborn`

**Salida principal:**  
- `analisis_corazon.png`: imagen con las visualizaciones generadas.
