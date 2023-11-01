# Análisis del Átomo de Hidrógeno: Comparación Analítica vs. Machine Learning

## Descripción

Este proyecto tiene como objetivo modelar la función de onda radial del átomo de hidrógeno usando dos enfoques: una solución analítica y un modelo de aprendizaje automático. La comparación entre ambos métodos proporciona una visión de cómo los modelos de machine learning pueden aproximarse a soluciones analíticas conocidas.

## Contenido

- **Solución Analítica**: Utiliza ecuaciones derivadas de la mecánica cuántica para calcular la función de onda radial para diferentes orbitales.
- **Solución de Machine Learning**: Utiliza una red neuronal para aprender la función de onda radial a partir de datos generados mediante la solución analítica.

## Uso

1. **Preparación de Datos**:
    - Genera datos para la función de onda radial del átomo de hidrógeno usando la solución analítica.
    - Divide los datos en conjuntos de entrenamiento y prueba.

2. **Modelo de Machine Learning**:
    - Construye y entrena una red neuronal profunda para modelar la función de onda radial.
    - Evalúa y compara el rendimiento del modelo con la solución analítica.

3. **Visualización**:
    - Grafica y compara las soluciones analíticas con las predicciones del modelo de machine learning.

## Resultados

Los modelos de machine learning, cuando se entrenan adecuadamente, pueden acercarse significativamente a las soluciones analíticas del átomo de hidrógeno. Estos modelos proporcionan una herramienta poderosa para aproximar soluciones en sistemas donde las soluciones analíticas pueden no ser conocidas o fáciles de calcular.

## Requisitos

- Python 3.8+
- TensorFlow 2.x
- NumPy
- Matplotlib
- Scipy
- Scikit-learn

## Instalación

\```bash
pip install tensorflow numpy matplotlib scipy scikit-learn
\```

## Ejecución

Para ejecutar el proyecto, simplemente ejecute el script principal:

\```bash
python main.py
\```

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue para discutir cualquier mejora o corrección que te gustaría aportar.

## Licencia

MIT
