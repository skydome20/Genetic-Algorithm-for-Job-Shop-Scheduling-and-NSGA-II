# Nondominated Sorting Genetic Algorithm II (NSGA-II) (cont.)


上一篇文章介紹了什麼是基因演算法(GA)，而本文介紹的非凌越排序基因演算法(NSGA-II)是由GA所延伸出來的演算法，專門用來求解具有多目標的問題，因此本篇文章將要介紹何謂NSGA-II，並在最後會透過PYTHON來進行實作，求解具有雙目標的排程Jop Shop問題。

### :black_nib: "凌越(dominated)"的概念是什麼? 
一般而言，在單目標問題中，我們可以很容易的判斷什麼是好的解、什麼是不好的解，但當我們遇到多目標問題時，解的品質就不是那麼容易判斷了，尤其是解跟解之間具有衝突時，因此，在多目標問題中會透過"凌越"的概念來判斷一組解的好壞。




### :black_nib: Reference 
[A Fast and Elitist Multiobjective Genetic Algorithm: NSGA-II ](https://ieeexplore.ieee.org/document/996017/)