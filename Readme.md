# GameOfLife 编程操练 nodejs 版本

Your task is to write a program to calculate the next
generation of Conway's game of life, given any starting
position.

You start with a two dimensional grid of cells, where
each cell is either alive or dead. The grid is finite,
and no life can exist off the edges. When calculating
the next generation of the grid, follow these four rules:

1. Any live cell with fewer than two live neighbours
   dies, as if caused by underpopulation.
2. Any live cell with more than three live neighbours
   dies, as if by overcrowding.
3. Any live cell with two or three live neighbours
   lives on to the next generation.
4. Any dead cell with exactly three live neighbours
   becomes a live cell.

Examples: * indicates live cell, . indicates dead cell

Example input: (4 x 8 grid)
4 8
........
....*...
...**...
........

Example output:
4 8
........
...**...
...**...
........

## 操练前准备工作

- 确保安装了node 8.0 以上的版本
- 安装了vscode/sublime
- 有一台可以访问外网的电脑
- 在项目根目录下运行`yarn`

## 开始操练

- `yarn install`
- `yarn test`
