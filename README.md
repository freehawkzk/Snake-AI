# Snake-AI

A snake game AI written in c/c++. ([中文博客](http://blog.csdn.net/qq_22885773/article/details/51888925))

## What can this program do?

* Play classic snake game.

* Watch how an AI snake eat food.

* Used as a console/terminal graphics library.

## Getting Started

Compile and run

```bash
$ make
$ make run
```

For usage, see function [main()](./src/main.cpp)

## Game Control

| Key | Feature |
|:---:|---------|
|W|move up|
|A|move left|
|S|move down|
|D|move right|
|Space|pause/resume game|
|Esc|terminate game|

## Demo

AI:

![](img/AI.gif)
   
Algorithm test

(the green areas are scanned by the search algorithm and red areas are the path)

* Dijkstra

   ![](img/dijkstra.gif)

* Dijkstra + A*

   ![](img/dijkstra_Astar.gif)

* Maze generate

   ![](img/maze.png)

## Todos

* Optimize AI algorithm.

  The algorithm for AI is not the best since there are some situations in which the snake kills itself after moving.

## License

See the [LICENSE](./LICENSE.md) file for license rights and limitations.
