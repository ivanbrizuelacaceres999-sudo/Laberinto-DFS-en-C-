# 🐭 Maze Solver C - DFS & Backtracking

Este es un generador y resolutor de laberintos desarrollado en **C**. Utiliza algoritmos de teoría de grafos para crear estructuras perfectas y encontrar el camino hacia la salida mediante una simulación de un ratón buscando queso.

## 🚀 Características

- **Generación Aleatoria:** Crea laberintos perfectos (sin ciclos) usando el algoritmo **Recursive Backtracker**.
- **Resolución Inteligente:** Utiliza **DFS (Depth-First Search)** con la técnica de **Backtracking** para encontrar la salida.
- **Memoria Dinámica:** Gestión eficiente de la RAM mediante punteros y `malloc/free`, permitiendo tamaños personalizados.
- **Interfaz de Consola:** Visualización clara en tiempo real del laberinto, el rastro del ratón y la solución.

## 🧠 Conceptos Aplicados

- **Grafos:** Representación implícita de una rejilla (Grid Graph).
- **LIFO (Last In, First Out):** Uso de la pila de llamadas (Stack) para la recursividad.
- **Backtracking:** Técnica de "ensayo y error" para retroceder ante callejones sin salida.
- **Memoria Viva:** Uso de argumentos de línea de comandos (`argc`, `argv`) para definir dimensiones en tiempo de ejecución.

## 🛠️ Instalación y Ejecución

### Requisitos
- Compilador GCC (MinGW, MSYS2 o similar).

### Compilación
Abre tu terminal en la carpeta del proyecto y ejecuta:
```bash
gcc laberinto.c -o laberinto.exe
