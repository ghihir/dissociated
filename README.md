# 概要
与えられた分子の座標データから、分子か分解しているかどうかの判定をする。

# input
```
82
C     58.67153    59.88961    62.38365
C     59.17532    60.45414    63.68124
C     60.14304    59.48700    64.39567
C     59.43849    58.23513    64.79791
C     61.54440    54.88075    66.10577
....
67
C     59.64892    62.78171    66.37829
N     61.17532    61.45414    61.45524
O     43.10443    59.48700    62.36277
....
```

# output
```
0         # 分解していなければ０
0
1         # 分解していれば１
0
1
```
...