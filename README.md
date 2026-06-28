# Clasificación multiclase con técnicas de aprendizaje profundo multitarea, y su aplicación a la detección de lesiones dérmicas

Repositorio de código del Trabajo de Fin de Grado (TFG) del Grado en Matemáticas de la Universitat de les Illes Balears (UIB).

**Autora:** Maria del Mar Tauler  
**Tutores:** Marc Munar Covas y Lídia Talavera Martínez 
**Curso:** 2025-2026

## Descripción

Este trabajo aborda la clasificación automática de lesiones dérmicas a partir de imágenes dermatoscópicas del conjunto de datos HAM10000, comparando cinco arquitecturas de redes neuronales convolucionales (VGG16, ResNet50, MobileNetV2, DenseNet169 y U-Net) en tres escenarios experimentales:

- **Monotarea - diagnóstico de enfermedad:** clasificación multiclase entre las siete categorías de patologías de HAM10000.
- **Monotarea - simetría:** clasificación de la simetría de la lesión.
- **Multitarea:** predicción simultánea de diagnóstico, simetría y malignidad mediante una arquitectura con cabeza compartida y tres capas de clasificación específicas, con ponderación dinámica de pérdidas mediante GradNorm.

El análisis estadístico de los resultados se realiza mediante bootstrap BCa estratificado con corrección de Bonferroni para las comparaciones por pares.

