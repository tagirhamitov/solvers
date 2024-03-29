# Solvers (made in SochiSirius2020 by Tagir Khamitov)

## Chess
To run *chess.py* use:

```
python3 chess.py
8
```

or

```
python3 chess.py 8
```
Yout can replace 8 with other length of board side.

Output format:

```
.......*
...*....
*.......
..*.....
.....*..
.*......
......*.
....*...
```

## Sudoku
To run *sudoku.py* use:

```
python3 sudoku.py
```
And enter sudoku in format:
```
5****34*7
***62****
****54**1
*7****8*6
**3***5**
8*5****2*
1**37****
****98***
4*81****5
```
Output format:
```
582|913|467
314|627|958
967|854|231
-----------
271|539|846
643|281|579
895|746|123
-----------
129|375|684
756|498|312
438|162|795
```

## Diagonals
To run *diagonals.py* use:

```
python3 diagonals.py
6
```

or

```
python3 chess.py 6
```
Yout can replace 6 with other length of board side.

Output format:

```
|/| |/| |/|/|
|/| |/| | |/|
|/| |/|/| |/|
|/| | |/| |/|
|/| | |/| | |
|/|/| |/|/|/|
Total 21 diagonals
```

## 4 in row
To run *4_in_row.py* use:
```
python3 4_in_row.py
```
And enter an example in format:
```
12 10
X....X.XX.
.X.XX...O.
O.XO.X..OX
..........
.X........
.OX...OO.X
O..X....X.
O..O..X...
........X.
OO....O.X.
.OO......X
OOO.O.X.XX
```
Output format:
```
XXOXOXOXXX
XXOXXOXOOO
OOXOXXXOOX
OXOOOXOXXX
OXXXOXOXOO
XOXOXOOOXX
OOXXXOXOXX
OXOOOXXXOO
XXOXOXOOXX
OOXXOOOXXO
XOOOXXXOOX
OOOXOOXOXX
```

## Cliques
To run *clique.py* use:
```
python3 clique.py
```
And enter a graph in format:
```
p e n m
e u1 v1
e u2 v2
...
```
Where n - number of vertices, m - number of edges, u<sub>i</sub> and v<sub>i</sub> - vertices connected with edge number i.

## Graph coloring
To run *graph_coloring.py* use:
```
python3 graph_coloring.py
```
And enter a graph in format:
```
p e n m
e u1 v1
e u2 v2
...
```
Where n - number of vertices, m - number of edges, u<sub>i</sub> and v<sub>i</sub> - vertices connected with edge number i.