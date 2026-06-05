# 🧪 NumPy & Procesamiento de Imágenes en Python

Un espacio dedicado al aprendizaje práctico de **NumPy**, manipulación de arreglos multidimensionales y análisis básico de imágenes utilizando Python y Jupyter Notebooks.

Este repositorio contiene libretas interactivas diseñadas para explorar los conceptos fundamentales de la computación científica y el procesamiento de imágenes digitales.

---

## 📁 Estructura del Proyecto

```text
numpy/
├── 1_numpy_avanzado.ipynb   # NumPy avanzado: arreglos, dimensiones y matrices aleatorias
├── 2_ejercicios.ipynb       # Análisis de imágenes (beagle.jpg) con Matplotlib
├── beagle.jpg               # Imagen de muestra para el análisis visual
└── .venv/                   # Entorno virtual con las dependencias instaladas
```

---

## 📓 Descripción de los Notebooks

### 1. 🧮 `1_numpy_avanzado.ipynb` - NumPy Avanzado
Notebook consolidado que combina la introducción a arreglos de NumPy con la generación y visualización de matrices aleatorias usando Python puro.

* **Parte 1 — Arreglos NumPy:**
  * Creación de arreglos multidimensionales con `np.array()` y `dtype='float'`.
  * Inspección de atributos esenciales:
    * `.ndim`: número de dimensiones.
    * `.shape`: dimensiones en formato de tupla `(filas, columnas)`.
    * `.size`: total de elementos.

* **Parte 2 — Matrices Aleatorias:**
  * Generación dinámica de matrices cuadradas $N \times N$ con `random.randint`.
  * Formateo simétrico en consola usando f-strings y `.join()`.
  * Ejemplos con matrices de $5 \times 5$, $10 \times 10$ y $20 \times 20$.

### 2. 🖼️ `2_ejercicios.ipynb` - Análisis de una Imagen
Procesamiento digital de imágenes: cómo una fotografía se representa como una matriz tridimensional en memoria.

* **Conceptos clave:**
  * Lectura de `beagle.jpg` con `plt.imread()` de Matplotlib.
  * Análisis de la estructura `(Alto, Ancho, Canales RGB)` mediante `.shape`.
  * Inspección de valores de píxeles individuales en coordenadas específicas (valores en rango $[0, 255]$).

---

## 🛠️ Requisitos e Instalación

### Dependencias Principales
* **NumPy** (`numpy`): cálculo numérico y arreglos multidimensionales.
* **Matplotlib** (`matplotlib`): lectura, procesamiento y visualización de imágenes.
* **Jupyter** (`notebook` / `jupyterlab`): ejecución de libretas interactivas.

### Configuración del Entorno

1. **Acceder al directorio:**
   ```bash
   cd numpy
   ```

2. **Activar el entorno virtual (`.venv`):**
   ```bash
   # macOS/Linux
   source .venv/bin/activate

   # Windows
   .venv\Scripts\activate
   ```

3. **Instalar dependencias** (entorno nuevo o limpio):
   ```bash
   pip install numpy matplotlib notebook
   ```

4. **Iniciar Jupyter:**
   ```bash
   jupyter notebook
   ```

---

## 🚀 ¿Cómo empezar?

1. Abre **`1_numpy_avanzado.ipynb`** para aprender las propiedades de los arreglos NumPy y practicar la generación de matrices aleatorias.
2. Continúa con **`2_ejercicios.ipynb`** para cargar `beagle.jpg` y explorar cómo se representa una imagen como una matriz 3D con canales RGB.

---
> [!NOTE]
> Este proyecto forma parte de una ruta de aprendizaje orientada a **Ciencia de Datos**, **Computación Científica** y **Procesamiento de Imágenes**. ¡Perfecto para entusiastas del análisis de datos que inician su viaje en Python!
