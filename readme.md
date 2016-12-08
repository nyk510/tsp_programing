# TSP Programing

TSP（循環セールスマン問題）を解きます。

## C

ｃ言語での実装

http://www-or.amp.i.kyoto-u.ac.jp/~shurbevski/

```bash
g++ -std=gnu++11 -O3 tsp_b.cpp -o tsp_program
tsp_program < tsp_instance
```

### 結果

```
The input graph is:
0: [(0,1),12], [(0,2),11], [(0,3),17], [(0,4),113], [(0,5),9],
1: [(1,0),12], [(1,2),9], [(1,3),125], [(1,4),13], [(1,5),16],
2: [(2,0),11], [(2,1),9], [(2,3),26], [(2,4),6], [(2,5),112],
3: [(3,0),17], [(3,1),125], [(3,2),26], [(3,4),8], [(3,5),23],
4: [(4,0),113], [(4,1),13], [(4,2),6], [(4,3),8], [(4,5),45],
5: [(5,0),9], [(5,1),16], [(5,2),112], [(5,3),23], [(5,4),45],

Starting calculation...
FINISHED!
	Elapsed Time: 0.225297 seconds.
Optimal Route Length: 65
The route:
0: [(0,3),17], [(0,5),9],
1: [(1,2),9], [(1,5),16],
2: [(2,1),9], [(2,4),6],
3: [(3,0),17], [(3,4),8],
4: [(4,2),6], [(4,3),8],
5: [(5,0),9], [(5,1),16],


```
