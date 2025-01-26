# **Clasificación de Manchas Cutáneas con Redes Neuronales Convolucionales (TFG)**

Este repositorio contiene el código desarrollado como parte del Trabajo Fin de Grado (TFG) titulado **"Clasificación de manchas cutáneas mediante redes neuronales convolucionales (CNN)"**, elaborado por **Isidoro Torres Díaz**.

## **Descripción del proyecto**

El objetivo de este TFG es desarrollar un modelo de clasificación de imágenes médicas utilizando redes neuronales convolucionales (CNN) para identificar manchas cutáneas benignas y malignas. Además, se explora la importancia de la explicabilidad en los modelos de inteligencia artificial aplicados a la medicina, empleando técnicas como **LIME (Local Interpretable Model-Agnostic Explanations)** para analizar las decisiones del modelo.

## **Estructura del repositorio**

- **`Skin_Cancer_CNN.ipynb`**: Notebook principal con el código utilizado para el preprocesamiento de datos, definición de modelos, entrenamiento, evaluación y análisis de resultados.
- **`/models`**: Carpeta opcional para guardar los modelos entrenados en formato `.pth` o `.h5`.
- **`README.md`**: Archivo actual que explica los detalles del repositorio.

## **Características del proyecto**

- **Modelos utilizados:**
  - Modelo personalizado.
  - Arquitecturas clásicas como **LeNet** y **AlexNet**.
- **Técnicas de validación:**
  - Validación cruzada estratificada (5 pliegues).
- **Explicabilidad:**
  - Implementación del método **LIME** para analizar las decisiones del modelo en imágenes médicas.

## **Cómo ejecutar el proyecto**

### **1. Clonar el repositorio**
```bash
git clone https://github.com/IsidoroTorres/TFG-Skin-Cancer-Classification.git
cd TFG-Skin-Cancer-Classification
