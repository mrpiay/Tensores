# Tensores Matemáticos: Introducción y Aplicaciones en Computación

> De los escalares a los qubits entrelazados — una guía progresiva sobre tensores y su aplicación en aprendizaje computacional y computación cuántica.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mrìay/Tensores/blob/main/Tensores_Notebook.ipynb)

## Descripción

Un recurso didáctico en español que explora los **tensores** desde tres perspectivas complementarias:

- **Física y Geometría** — Qué es un tensor, cómo se transforma, qué permanece invariante.
- **Machine Learning** — Tensores como contenedores multidimensionales: desde escalares hasta batches de imágenes, pasando por una red neuronal paso a paso.
- **Computación Cuántica** — Qubits como vectores complejos, puertas cuánticas como matrices, producto tensorial, entrelazamiento y el algoritmo de Deutsch-Jozsa.

## Contenido

El notebook integra teoría y código en cada sección:

| Parte | Secciones | Temas clave |
|-------|-----------|-------------|
| **1. Fundamentos** | 1–7 | Arrays vs tensores, orden, transformaciones, invariantes |
| **2. Machine Learning** | 8–13 | Jerarquía de datos, operaciones, red MNIST, batches, PyTorch |
| **3. Computación Cuántica** | 14–20 | Qubits, puertas cuánticas, producto tensorial, entrelazamiento, Deutsch-Jozsa |
| **Conclusión** | — | Mapa comparativo, glosario |

## Requisitos

Solo necesitas `numpy` y `matplotlib`. El notebook los instala automáticamente al ejecutar la primera celda.

```
pip install numpy matplotlib
```

PyTorch es opcional (sección 13).

## Uso

1. Abre el notebook en Google Colab con el badge de arriba (actualiza el enlace con tu usuario y repo).
2. O clónalo y ejecútalo localmente:

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
jupyter notebook Tensors_Notebook.ipynb
```

## Autor

**Mr. Piay**

## Licencia

Este proyecto se distribuye bajo la licencia [MIT](LICENSE).
