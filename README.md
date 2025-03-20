# Minimum-Sum-absoulte-difference-Pair

Min Absolute Difference Pairs
Given two arrays A and B of equal length n. Pair each element of array A to an element in array B, such that the sum S of absolute differences of all the pairs is minimum.

Given Data:
A = [1, 2, 3]
B = [2, 1, 3]

Cases:
Case 1: |1 - 2| + |2 - 1| + |3 - 3| = 1 + 1 + 0 = 2 ✅✅
Case 2: |1 - 3| + |2 - 1| + |3 - 2| = 2 + 1 + 1 = 4 ✅
Case 3: |1 - 1| + |2 - 2| + |3 - 3| = 0 + 0 + 0 = 0 ✅

Answer:
ans = 0


Approach

a ⟷ b
(close)
(abs. difference ↓)

1 ⟷ 5 → 4
1 ⟷ 100 → 99

Given Data:
A = [4, 1, 8, 7]
B = [2, 3, 6, 5]

Sorting the arrays:
Sorted A = [1, 4, 7, 8]
Sorted B = [2, 3, 5, 6]

Calculating absolute differences:
|1 - 2| = 1
|4 - 3| = 1
|7 - 5| = 2
|8 - 6| = 2

Total sum:
1 + 1 + 2 + 2 = 6