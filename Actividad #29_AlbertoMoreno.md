# Fundamentos de Álgebra — Ejercicios 13 al 36

---

## Encuentra la inversa de las siguientes matrices

### 13)

$$
A = \begin{bmatrix} 3 & -4 & -1 \\ -1 & 2 & 2 \\ -3 & -1 & 2 \end{bmatrix}
$$

- **Determinante:** $\det(A) = 27$
- **Matriz inversa:**

$$
A^{-1} = \begin{bmatrix} \frac{2}{9} & \frac{1}{3} & -\frac{2}{9} \\ -\frac{4}{27} & \frac{1}{9} & -\frac{5}{27} \\ \frac{7}{27} & \frac{5}{9} & \frac{2}{27} \end{bmatrix}
$$

---

### 14)

$$
A = \begin{bmatrix} 3 & 0 & 2 \\ 4 & 5 & -2 \\ -1 & -3 & -4 \end{bmatrix}
$$

- **Determinante:** $\det(A) = -92$
- **Matriz inversa:**

$$
A^{-1} = \begin{bmatrix} \frac{13}{46} & \frac{3}{46} & \frac{5}{46} \\ -\frac{9}{46} & \frac{5}{46} & -\frac{7}{46} \\ \frac{7}{92} & -\frac{9}{92} & -\frac{15}{92} \end{bmatrix}
$$

---

### 15)

$$
A = \begin{bmatrix} -1 & 4 & -4 \\ 0 & -3 & 4 \\ 0 & 0 & 0 \end{bmatrix}
$$

- **Determinante:** $\det(A) = 0$ (la última fila es completamente de ceros).
- **Resultado:** **No tiene inversa** (es una matriz singular).

---

### 16)

$$
A = \begin{bmatrix} 6 & -5 & 1 \\ -4 & 6 & -3 \\ 2 & 6 & -2 \end{bmatrix}
$$

- **Determinante:** $\det(A) = 70$
- **Matriz inversa:**

$$
A^{-1} = \begin{bmatrix} \frac{3}{35} & -\frac{2}{35} & \frac{9}{70} \\ -\frac{1}{5} & -\frac{1}{5} & \frac{1}{5} \\ -\frac{18}{35} & -\frac{23}{35} & \frac{8}{35} \end{bmatrix}
$$

---

### 17)

$$
A = \begin{bmatrix} 1 & -5 & -5 \\ 7 & -3 & -1 \\ -2 & -6 & 0 \end{bmatrix}
$$

- **Determinante:** $\det(A) = 224$
- **Matriz inversa:**

$$
A^{-1} = \begin{bmatrix} -\frac{3}{112} & \frac{15}{112} & -\frac{5}{112} \\ \frac{1}{112} & -\frac{5}{112} & -\frac{17}{112} \\ -\frac{3}{14} & \frac{1}{14} & \frac{1}{7} \end{bmatrix}
$$

---

### 18)

$$
A = \begin{bmatrix} -5 & 1 & -4 \\ -3 & -6 & -4 \\ -1 & -1 & -4 \end{bmatrix}
$$

- **Determinante:** $\det(A) = -96$
- **Matriz inversa:**

$$
A^{-1} = \begin{bmatrix} -\frac{5}{24} & -\frac{1}{12} & \frac{7}{24} \\ \frac{1}{12} & -\frac{1}{6} & \frac{1}{12} \\ \frac{1}{32} & \frac{1}{16} & -\frac{11}{32} \end{bmatrix}
$$

---

### 19)

$$
A = \begin{bmatrix} -1 & -1 & -3 \\ -6 & -6 & -3 \\ 3 & 6 & -2 \end{bmatrix}
$$

- **Determinante:** $\det(A) = 45$
- **Matriz inversa:**

$$
A^{-1} = \begin{bmatrix} \frac{2}{3} & -\frac{4}{9} & -\frac{1}{3} \\ -\frac{7}{15} & \frac{11}{45} & \frac{1}{3} \\ -\frac{2}{5} & \frac{1}{15} & 0 \end{bmatrix}
$$

---

### 20)

$$
A = \begin{bmatrix} -2 & 2 & -2 \\ 5 & -2 & 1 \\ -1 & 5 & 3 \end{bmatrix}
$$

- **Determinante:** $\det(A) = -56$
- **Matriz inversa:**

$$
A^{-1} = \begin{bmatrix} \frac{11}{56} & \frac{2}{7} & \frac{1}{28} \\ \frac{2}{7} & \frac{1}{7} & \frac{1}{7} \\ -\frac{23}{56} & -\frac{1}{7} & \frac{3}{28} \end{bmatrix}
$$

---

## Calcula el determinante usando la regla de Sarrus

### 21)

$$
\begin{vmatrix} -6 & 0 & -3 \\ 3 & 4 & -8 \\ 10 & 7 & 11 \end{vmatrix} = \big[(-6)(4)(11) + (0)(-8)(10) + (-3)(3)(7)\big] - \big[(-3)(4)(10) + (-6)(-8)(7) + (0)(3)(11)\big]
$$

$$
= (-264 + 0 - 63) - (-120 + 336 + 0) = -327 - 216 = \mathbf{-543}
$$

---

### 22)

$$
\begin{vmatrix} 10 & -5 & 0 \\ 7 & -2 & -1 \\ 5 & -3 & 1 \end{vmatrix} = \big[(10)(-2)(1) + (-5)(-1)(5) + (0)(7)(-3)\big] - \big[(0)(-2)(5) + (10)(-1)(-3) + (-5)(7)(1)\big]
$$

$$
= (-20 + 25 + 0) - (0 + 30 - 35) = 5 - (-5) = \mathbf{10}
$$

---

### 23)

$$
\begin{vmatrix} -9 & 11 & 5 \\ 9 & 10 & 0 \\ -2 & 9 & 10 \end{vmatrix} = \big[(-9)(10)(10) + (11)(0)(-2) + (5)(9)(9)\big] - \big[(5)(10)(-2) + (-9)(0)(9) + (11)(9)(10)\big]
$$

$$
= (-900 + 0 + 405) - (-100 + 0 + 990) = -495 - 890 = \mathbf{-1385}
$$

---

### 24)

$$
\begin{vmatrix} 5 & -7 & 12 \\ -11 & -5 & 7 \\ 1 & 10 & 11 \end{vmatrix} = \big[(5)(-5)(11) + (-7)(7)(1) + (12)(-11)(10)\big] - \big[(12)(-5)(1) + (5)(7)(10) + (-7)(-11)(11)\big]
$$

$$
= (-275 - 49 - 1320) - (-60 + 350 + 847) = -1644 - 1137 = \mathbf{-2781}
$$

---

### 25)

$$
\begin{vmatrix} -8 & 5 & 11 \\ 2 & 1 & 10 \\ 2 & 12 & 4 \end{vmatrix} = \big[(-8)(1)(4) + (5)(10)(2) + (11)(2)(12)\big] - \big[(11)(1)(2) + (-8)(10)(12) + (5)(2)(4)\big]
$$

$$
= (-32 + 100 + 264) - (22 - 960 + 40) = 332 - (-898) = \mathbf{1230}
$$

---

### 26)

$$
\begin{vmatrix} -7 & 8 & 2 \\ 1 & -3 & 2 \\ 0 & 4 & 1 \end{vmatrix} = \big[(-7)(-3)(1) + (8)(2)(0) + (2)(1)(4)\big] - \big[(2)(-3)(0) + (-7)(2)(4) + (8)(1)(1)\big]
$$

$$
= (21 + 0 + 8) - (0 - 56 + 8) = 29 - (-48) = \mathbf{77}
$$

---

### 27)

$$
\begin{vmatrix} -6 & -4 & -11 \\ 3 & -9 & 6 \\ -12 & 1 & -11 \end{vmatrix} = \big[(-6)(-9)(-11) + (-4)(6)(-12) + (-11)(3)(1)\big] - \big[(-11)(-9)(-12) + (-6)(6)(1) + (-4)(3)(-11)\big]
$$

$$
= (-594 + 288 - 33) - (-1188 - 36 + 132) = -339 - (-1092) = \mathbf{753}
$$

---

### 28)

$$
\begin{vmatrix} 0 & 12 & 3 \\ 6 & 6 & -4 \\ -7 & -3 & -8 \end{vmatrix} = \big[(0)(6)(-8) + (12)(-4)(-7) + (3)(6)(-3)\big] - \big[(3)(6)(-7) + (0)(-4)(-3) + (12)(6)(-8)\big]
$$

$$
= (0 + 336 - 54) - (-126 + 0 - 576) = 282 - (-702) = \mathbf{984}
$$

---

## Calcula el determinante usando el método de cofactores

### 29)

$$
\begin{vmatrix} -6 & 1 & 5 & 8 & -7 \\ 3 & 9 & 9 & -3 & -6 \\ 6 & 5 & 0 & -10 & -5 \\ 4 & 0 & -1 & -3 & -7 \\ 9 & 10 & 2 & -10 & -4 \end{vmatrix}
$$

Expandiendo por la **fila 3**:

$$
\det = (+6)(-3420) - (5)(189) + (0) - (-10)(3033) + (-5)(-639)
$$

$$
\det = -20520 - 945 + 30330 + 3195 = \mathbf{12060}
$$

---

### 30)

$$
\begin{vmatrix} -8 & -9 & 9 & 0 & 0 \\ 4 & -9 & 4 & -1 & 7 \\ 4 & -7 & -3 & 7 & -1 \\ 2 & 9 & 5 & 7 & -4 \\ -9 & -10 & 5 & -3 & 4 \end{vmatrix}
$$

Expandiendo por la **fila 1** (aprovechando los dos ceros):

$$
\det = (-8)(-4611) - (-9)(-4437) + (9)(-5394)
$$

$$
\det = 36888 - 39933 - 48546 = \mathbf{-51591}
$$

---

### 31)

$$
\begin{vmatrix} 3 & 2 & 7 & -8 & -10 \\ -1 & 6 & 6 & 0 & -2 \\ -1 & 5 & 2 & -9 & 2 \\ 0 & 3 & 5 & 2 & -7 \\ -2 & 8 & 0 & 9 & 10 \end{vmatrix}
$$

Expandiendo por la **fila 2**:

$$
\det = -(-1)(-1419) + (6)(2111) - (6)(3217) + (0) - (-2)(1396)
$$

$$
\det = -1419 + 12666 - 19302 + 2792 = \mathbf{-5263}
$$

---

### 32)

$$
\begin{vmatrix} -1 & -8 & -4 & 6 & -4 \\ -1 & -8 & 1 & -10 & 9 \\ 6 & -7 & 7 & 8 & 9 \\ -9 & 7 & 10 & 8 & 8 \\ -5 & 6 & 9 & 0 & 3 \end{vmatrix}
$$

Expandiendo por la **fila 5**:

$$
\det = (-5)(-2128) - (6)(10844) + (9)(32058) - (0) + (3)(-23722)
$$

$$
\det = 10640 - 65064 + 288522 - 71166 = \mathbf{162932}
$$

---

### 33)

$$
\begin{vmatrix} 10 & -10 & -2 & 4 & 4 \\ 2 & 4 & 9 & 2 & 2 \\ 2 & -5 & -3 & 6 & -8 \\ 5 & 10 & 6 & -3 & 4 \\ 1 & 8 & -4 & 2 & 3 \end{vmatrix}
$$

Expandiendo por la **fila 1**:

$$
\det = (10)(3531) - (-10)(2382) + (-2)(-738) - (4)(-1089) + (4)(3465)
$$

$$
\det = 35310 + 23820 + 1476 + 4356 + 13860 = \mathbf{78822}
$$

---

### 34)

$$
\begin{vmatrix} -5 & -9 & 10 & 8 & 0 \\ -5 & -9 & -2 & 0 & 10 \\ 3 & -4 & -5 & -10 & 2 \\ 1 & 8 & -6 & -4 & -6 \\ 7 & -3 & 3 & -1 & -3 \end{vmatrix}
$$

Expandiendo por la **fila 1**:

$$
\det = (-5)(-1942) - (-9)(1704) + (10)(198) - (8)(493) + (0)
$$

$$
\det = 9710 + 15336 + 1980 - 3944 = \mathbf{23082}
$$

---

### 35)

$$
\begin{vmatrix} 2 & 0 & -5 & -4 & 0 \\ 8 & 10 & 8 & 10 & -5 \\ 10 & -9 & 3 & -4 & -3 \\ -3 & 9 & 4 & -8 & 3 \\ 2 & -8 & 2 & -1 & -6 \end{vmatrix}
$$

Expandiendo por la **fila 1** (aprovechando los dos ceros):

$$
\det = (2)(4505) - (0) + (-5)(-12905) - (-4)(4900) + (0)
$$

$$
\det = 9010 + 64525 + 19600 = \mathbf{93135}
$$

---

### 36)

$$
\begin{vmatrix} -5 & -5 & -5 & -9 & -5 \\ -9 & 1 & -1 & -2 & -1 \\ 3 & 2 & -9 & 0 & 8 \\ -9 & -8 & -2 & -4 & -3 \\ 4 & 4 & 1 & 3 & 7 \end{vmatrix}
$$

Expandiendo por la **fila 3**:

$$
\det = (3)(-45) - (2)(9) + (-9)(-2709) - (0) + (8)(-315)
$$

$$
\det = -135 - 18 + 24381 - 2520 = \mathbf{21708}
$$
