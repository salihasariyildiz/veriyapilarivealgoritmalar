# Binary Search Tree Projesi

1. [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Öncelikle root belirlenir, root'tan küçük olanlar sol tarafta büyük olanlar sağ tarafta toplanır. 

1.Adım: Root belirlemek.
Root: 7

2.Adım: 5<7

``` 
                    7
                   /
                  5
``` 

3.Adım: 1<7

``` 
                    7
                   /
                  5 
                 /
                1
``` 

4.Adım: 8>7

``` 
                    7
                   / \
                  5   8
                 /
                1
``` 

5.Adım: 3<7

``` 
                    7
                   / \
                  5   8
                 /
                1
                 \
                  3
``` 

6.Adım: 6<7

```  
                    7
                   / \
                  5   8
                 / \
                1   6
                 \
                  3
```  

7.Adım: 0<7

```  

                    7
                   / \
                  5   8
                 / \
                1   6
               / \
              0   3
```  

8.Adım: 9>7

``` 
                    7
                   / \
                  5   8
                 / \   \
                1   6   9
               / \
              0   3
```

9.Adım: 4<7

```
                    7
                   / \
                  5   8
                 / \   \
                1   6   9
               / \
              0   3
                   \
                    4
```

10.Adım: 2<7

```
                    7
                   / \
                  5   8
                 / \   \
                1   6   9
               / \
              0   3
                 / \
                2   4
