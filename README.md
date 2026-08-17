# graphs

## 1
TODO:

- Сравниваем Lagraph и SPLA
- Найти датасет
- Запустить готовые реализации:
    1. BFS (Breadth-first search)
    2. PR (PageRank)
    3. SSSP (Single Shortest Source Path problem)
    4. TC (Triangle Count)
- Посчитать на CPU и GPU, зафиксировав гиперпараметры
- Должны быть какие-то +- одинаковые результаты

## 2
```
cd Galois
```
```
exp/bfs.sh
exp/tc.sh
exp/sssp.sh
exp/pagerank.sh
```

TODO:
1. Понять, что за накладные расходы участвуют в подсчете времени 
2. Почему по кол-ву числа потоков ухудшается производительность на накладные расходы
3. BFS и SSSP нужна хоть какая-нибудь гипотеза, почему на 7 и 8 потоках так проседает производительность
4. Сделать так, чтоб был ReplicationFactor в парсере и CSV-таблице
5. ReduceNumMessages_BFS таблица
