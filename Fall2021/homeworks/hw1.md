# Homework 1 (Due xx/xx/xx)

### Objective
- Warmup and introduction to *time complexity*. 


## Problem 1 (25pts)
Let `P` be an array of integers. Write the function `Average(P)` that return the average of the integers in `P`.

## Problem 2 (25pts)
Given an array `A` of positive integers and an integer `k`. Write the function `multiplesOfK(A, k)` that counts all pairs `x, y` from `A` such that `x*y` is divisible by `k`.    


## Problem 3 (25pts)
Write the function `EqualStrings(A, B)` that take two arrays of strings `A` and `B` as an input and return `True` if the concatenation of strings in `A` equals the concatenation of strings in `B`. Otherwise, return `False`.

#### Sample input 1
```text 
input: A = ["w", "c", "x"], B = ["w", "cx"]
output: True
EXplanation: 
Concatenation of strings in A = "w" + "c" + "x" = "wcx".
Concatenation of strings in B = "w" + "cx" = "wcx".
```
#### Sample input 2
```text 
input: 
  A = ["w", "c", "xx", "y"], B = ["w", "cxx", "y", "z"]
output:
  False
Explanation: 
  Concatenation of strings in A = "w" + "c" + "xx" + "y" = "wcxxy".
  Concatenation of strings in B = "w" + "cxx" + "y" + "z" = "wcxxyz".
```
## Problem 4 (25pts)
Write the function `MaxTriangle(P)`
that takes an array of points `P`  (where `P[ i ] = [ x_i, y_i ]`) and return the largest possible triangle formed by 3 different points from `P`.  

#### Sample input 1
```text 
input: 
  P = [[0,0], [1, 1], [10, 0]]
output:
  5.0
Explanation:
  We can form only one triangle and its size is 5.0.
```
#### Sample input 2
```text 
input: 
  P = [[0, 1], [1, -10], [9, -7], [2, 3]]
output:
  50.5
Explanation:
  The largest triangle is formed from the points [1, -10],  [9, -7], [2, 3] or the points [0, 1], [9, -7], [2, 3].
 ```
