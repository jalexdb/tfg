# TFG: Simulaciones de avalanchas neuronales en redes estocásticas

Este repositorio contiene el código desarrollado para el Trabajo Fin de Grado (TFG) que estudia la dinámica de redes neuronales excitadoras e inhibitorias bajo estocasticidad intrínseca.  

El objetivo principal es explorar el fenómeno de **avalanchas neuronales** y la aparición de dinámicas colectivas en sistemas con **no-normalidad** y **reactividad**, usando modelos basados en Wilson-Cowan y simulaciones tipo Gillespie.

## 📄 Descripción

Las redes neuronales pueden presentar actividad espontánea en forma de avalanchas, caracterizadas por patrones de actividad que siguen distribuciones en ley de potencias.  
En este trabajo se emplea:
- Una aproximación estocástica mediante el **algoritmo de Gillespie**, que permite simular la dinámica discreta de poblaciones de neuronas.
- Análisis de la influencia de la **no-normalidad** (matrices de estabilidad no simétricas) en la amplificación de fluctuaciones y la aparición de avalanchas.

## 📁 Contenido

- `gillespie_matrix.ipynb`: Notebook principal que implementa la simulación estocástica usando el algoritmo de Gillespie para redes con poblaciones excitadoras e inhibitorias.
- `graficas.ipynb`: Notebook para analizar y visualizar los resultados (estadísticas de avalanchas, distribuciones, fases, etc.).

## Requisitos

- Python 3.8 o superior
- Jupyter Notebook
- Paquetes:
  - `numpy`
  - `matplotlib`
  - `scipy`

Puedes instalar las dependencias con:

```bash
pip install numpy matplotlib scipy
```

## Ejecución
 - Clonar el repositorio
```bash
git clone https://github.com/jalexdb/tfg.git
cd tfg
```
 - Abrir el notebook principal:
```bash
jupyter notebook gillespie_matrix.ipynb
```
 - Ejecutar todas las celdas para realizar la simulación
 - (Opcional) Abrir "graficas.ipynb" para generar y analizar gráficos adicionales de los resultados.
