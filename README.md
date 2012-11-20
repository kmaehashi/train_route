Train Route: Pseudo Shortest Path by Hops
=========================================

```
$ jubagraph &

$ ./create_graph.py
=== Station IDs ===
0       品川
1       大崎
4       田町
...
139     中野
144     四ツ谷
147     御茶ノ水

$ ./search_route.py 0 144
Pseudo-Shortest Path (hops) from 0 to 144:
  0     品川
  4     田町
  7     浜松町
  10    新橋
  13    有楽町
  16    東京
  19    神田
  147   御茶ノ水
  144   四ツ谷
```

This program uses [駅データ.jp](http://www.ekidata.jp/) to build graphs. (Thanks!)
