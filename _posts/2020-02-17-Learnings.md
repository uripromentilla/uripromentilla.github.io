# Learnings for 02-17\~23

### What is the solution to the nullspace?

Given Ax = 0. The set of numbers 'x' that will transform A to 0.

### What is a rank?

The number of pivot columns.

Given a \[n x m\] matrix, rank = n – pivot columns

### What is a pivot column?

The columns with the pivot. Pivots are the numbers you used during elimination to transform matrix A to echelon form.

### What is a free column?

The columns without a pivot.

### What is echelon form?

Echelon means stairs. It's when below the matrix's pivot, are all 0s.

### What is the reduced echelon form?

It's when it's in echelon form but also the pivots are normalized to 1.

### How do you find the solutions to the nullspace?

Given Ax = 0

1.  Elimination of A -\> Echelon form

2.  Echelon form -\> Equations

3.  Back-substitution -\> Solutions
    
    1.  set free columns to 1, then 0,
    
    2.  then substitute into equations,
    
    3.  then derive the rest.

4.  Solution = c \[x\]
    
    1.  because \[x\] is the basis for the nullspace
    
    2.  but all the possible solutions are the scaling of \[x\]

Another way using reduced echelon form:

1.  Elimination of A -\> Echelon form

2.  Echelon form -\> Reduced Echelon form

3.  Reduced Echelon form -\> Solutions
    
    1.  Reduced Echelon form = R
    
    2.  R = \[I F

> 0 0\]

3.  Given Rx = 0

4.  Then, N = \[-F

> I\]

5.  N = nullspace vector = basis for nullspace

<!-- end list -->

4.  Solutions = c \[N\]
    
    1.  all the possible solutions are the scaling of the nullspace basis vector

## How can you approximate in calculus?

You only need this formula:

f'(a) \~\~= f(x) – f(a) / x – a

What is the linear approximation formula?

f(x) = f(a) + (x-a)\*f'(a)

What is Newton's method formula?

Given f(x) = 0

x-a = -f(a)/f'(a)

## What is variance?

It represents the randomness of a random variable.

Expectation(X) = Mean of X

Variance = Summation\[ (X – mean)^2 \] / N

Variance = E\[X^2\] – (E\[X\])^2

## What is generalized policy iteration?

The idea of policy evaluation and improvement interacting with each other (to reach an optimal policy).
