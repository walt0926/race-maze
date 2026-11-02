# Race Maze

Race Maze es un videojuego desarrollado en Python utilizando la biblioteca Pygame. El proyecto combina la generación de laberintos, el movimiento de vehículos y la implementación de algoritmos de búsqueda para crear un juego basado en la exploración y resolución de caminos.

El objetivo principal es recorrer un laberinto, recolectar las monedas disponibles y llegar a la meta para completar cada nivel.

Este proyecto fue desarrollado como una aplicación práctica de los algoritmos de búsqueda **Depth-First Search (DFS)** y **Breadth-First Search (BFS)**.

## Características

- Generación aleatoria de laberintos.
- Sistema de movimiento y control de vehículos.
- Detección de colisiones con las paredes.
- Recolección de monedas dentro del laberinto.
- Sistema de niveles y progreso.
- Búsqueda de rutas mediante el algoritmo BFS.
- Generación de caminos mediante el algoritmo DFS.
- Interfaz gráfica desarrollada con Pygame.
- Sistema de selección y personalización de vehículos.

## Algoritmos implementados

### Depth-First Search (DFS)

El algoritmo DFS se utiliza para generar los laberintos del juego.

Su funcionamiento consiste en recorrer las celdas de una cuadrícula, seleccionando caminos y eliminando paredes entre las celdas visitadas. Esto permite generar diferentes estructuras de laberintos en cada partida.

### Breadth-First Search (BFS)

El algoritmo BFS se utiliza para encontrar el camino más corto desde una posición inicial hasta un objetivo dentro del laberinto.

A diferencia de DFS, BFS explora las posiciones por niveles, lo que permite encontrar una ruta óptima cuando todos los movimientos tienen el mismo costo.

### Comparación

| Algoritmo | Función dentro del proyecto |
|---|---|
| DFS | Generación de laberintos aleatorios |
| BFS | Búsqueda del camino más corto |

## Tecnologías utilizadas

- **Python:** lenguaje principal de programación.
- **Pygame:** desarrollo de la interfaz gráfica, movimiento y mecánicas del juego.
- **Algoritmos de búsqueda:** implementación de DFS y BFS.
- **Programación orientada a objetos:** organización de los componentes y funcionalidades del proyecto.

## Funcionamiento

Al iniciar una partida, el sistema genera un laberinto utilizando DFS. El jugador debe desplazarse por los caminos disponibles, evitando las paredes y recolectando las monedas distribuidas en el escenario.

Una vez recolectadas todas las monedas, puede dirigirse hacia la salida para completar el nivel.

El juego también incorpora BFS para calcular rutas dentro del laberinto, aplicando conceptos de estructuras de datos y búsqueda en grafos.

## Objetivo del proyecto

El propósito de Race Maze es aplicar conocimientos de programación, estructuras de datos y algoritmos de búsqueda en el desarrollo de un videojuego funcional.

A través de este proyecto se trabajan conceptos como la generación procedural de escenarios, el recorrido de grafos, la detección de colisiones y el desarrollo de interfaces gráficas con Python.

## Estado del proyecto

Proyecto académico desarrollado con Python y Pygame, enfocado en la implementación práctica de los algoritmos DFS y BFS.

## Autores

- **Walter Santos**
- **Patricia Alvarado**

Programa ¡Supérate! Fundación Frech
