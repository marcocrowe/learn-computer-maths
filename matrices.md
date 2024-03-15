# Matrices

An introduction to (2 dimensional) matrices for beginners.

## Introduction

A matrix is a rectangular array of numbers, symbols, or expressions, arranged in rows and columns. The individual items in a matrix are called its elements or entries. The horizontal and vertical lines of entries in a matrix are called rows and columns, respectively.

A matrix with m rows and n columns is called an m × n matrix or m-by-n matrix, while m and n are called its dimensions.
e.g. A matrix with 2 rows and 3 columns is called a 2 × 3 matrix or 2-by-3 matrix.

$`\begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \end{bmatrix}`$

```python
a = [
  [1, 2, 3],
  [4, 5, 6]
]

print(a)
```

## What are matrices used for?

Matrices are used to represent and solve systems of linear equations, to represent geometric transformations. They are used in fields such as: computer graphics, computer vision, robotics.

## Matrix Notation

A matrix is usually denoted by a capital letter. The elements of a matrix are usually denoted by the same letter in lowercase with a subscript indicating the row and column. For example, the element in the first row and first column of a matrix A is denoted by $`a_{1, 1}`$ or $`a_{11}`$ or , the element in the second row and first column is denoted by $`a_{2, 1}`$, and so on. In some cases, the element in the first row and first column is denoted by a11, the element in the first row and second column is denoted by a12, and so on.

, the element in the first row and second column is denoted by a12, and so on.

$`A=\begin{bmatrix} a_{11} & a_{12} & \dots & a_{1n} \\ a_{21} & a_{22} & \dots & a_{2n} \\ \vdots & \vdots & \ddots & \vdots \\ a_{m1} & a_{m2} & \dots & a_{mn} \end{bmatrix}`$
or
$`A=\begin{bmatrix} a_{1, 1} & a_{1, 2} & \dots & a_{1, n} \\ a_{2, 1} & a_{2, 2} & \dots & a_{2, n} \\ \vdots & \vdots & \ddots & \vdots \\ a_{m, 1} & a_{m, 2} & \dots & a_{m, n} \end{bmatrix}`$

$`A=\begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \end{bmatrix}`$
$`a_{11} = 1, a_{12} = 2, a_{13} = 3, a_{21} = 4, a_{22} = 5, a_{23} = 6`$
$`a_{1, 1} = 1, a_{1, 2} = 2, a_{1, 3} = 3, a_{2, 1} = 4, a_{2, 2} = 5, a_{2, 3} = 6`$

```python
a = [
  [1, 2, 3],
  [4, 5, 6]
]
print(a[0][0]) # 1
print(a[0][1]) # 2
print(a[0][2]) # 3
print(a[1][0]) # 4
print(a[1][1]) # 5
print(a[1][2]) # 6
```

## Types of Matrices

### Row Matrix

A matrix with only one row is called a row matrix.

$`\begin{bmatrix} 1 & 2 & 3 & 4 & 5\end{bmatrix}`$

```markdown
[1 2 3 4 5]
```

### Column Matrix

A matrix with only one column is called a column matrix.

$`\begin{bmatrix} 1 \\ 2 \\ 3 \\ 4 \\ 5\end{bmatrix}`$

### Square Matrix

A matrix with the same number of rows and columns is called a square matrix.

### Diagonal Matrix

A square matrix in which all the elements are zero except for the elements in the main diagonal is called a diagonal matrix.

### Scalar Matrix

A diagonal matrix in which all the elements in the main diagonal are equal is called a scalar matrix.

### Identity Matrix

A diagonal matrix in which all the elements in the main diagonal are equal to 1 is called an identity matrix.
