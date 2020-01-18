# 2D-Array---DS


Context 
Given a  6x6 Matrix A:

1 1 1 0 0 0
0 1 0 0 0 0
1 1 1 0 0 0
0 0 0 0 0 0
0 0 0 0 0 0
0 0 0 0 0 0

We define an hourglass in to be a subset of values with indices falling in this pattern in 's graphical representation:

a b c
  d
e f g
There are 16 hourglasses in the matrix A, and an hourglass sum is the sum of an hourglass' values.

You have to find the maximum hourglass sum

Task
Calculate the hourglass sum for every hourglass in A, then print the maximum hourglass sum.

 

Input Format

There are  lines of input, where each line contains  space-separated integers describing 2D Array A; every value in  will be in the inclusive range of -9 to 9.

Constraints

-9 <= A[i][j] <= 9
0 <= i,j <= 5
Output Format

Print the largest (maximum) hourglass sum found in A.

