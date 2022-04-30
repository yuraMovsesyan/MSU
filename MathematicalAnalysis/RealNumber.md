# Вещественное число

$\N := \{ 1,2,3,4,5,6, \dots \}$ − натуральное множество

$\Z := \{ 0, \pm 1, \pm 2, \pm 3, \dots \}$ - целое множество

$\mathbb{Q} = \{ \frac{n}{m} | n \in \Z, m \in \N \}$ − рациональное множество

$\R$ − это множественно вещественных чисел, а его элементы вещественные числа, если для них выполнены условия аксиоматики вещественных чисел.

**Вещественные числа** - множество + 2 операции сложение и умножение + одно отношение $\leq$ + набор из 16 свойств

## Операции

$a = b \iff a-b=0$

$a > b \iff a-b > 0$

$a < b \iff a-b < 0$

********$a \leq b \iff (a < b) \vee (a = b)$********

********$a \geq b \iff (a > b) \vee (a = b)$********

### Аксиоматический

1. $a+b=b+a$
2. $a + 0 = 0 + a = a$
3. $\exists b : a + b = b + a = 0$
4. $(a + b) + c = a + (b + c)$
5. $a \cdot b = b \cdot a$
6. $a \cdot 1 = 1 \cdot a = a$
7. $\exists b : a \cdot b = b \cdot a = 1$
8. $(a \cdot b) \cdot c = a \cdot (b \cdot c)$
9. $(a + b) \cdot c = a \cdot c + b \cdot c$
10. $a \leq a$
11. $a \leq b \wedge b \leq c \implies a \leq c$
12. $a \leq b \vee b \leq a$
13. $a \leq b \wedge b \leq a \implies a = b$
14. $a \leq b \implies a + c \leq b + c$
15. $a \leq b \wedge c > 0 \implies a \cdot c \leq b \cdot c$
16. $\R = A \sqcup B  \wedge \forall a \in A \quad \forall b \in B: a\leq b \implies \exist q: \forall a \in A \quad \forall b \in B: a \leq q \leq b$

**Аксиома полноты**
```
Для двух непересекающихся непустых подмножеств множества вещественных чисел А и Б для которых  любой элемент из А меньше или равно  любому элементу из Б существует число q такое что больше или равно элементу из А и меньше или равно элементу из Б.
```

## sup и inf

`Множество, ограниченное и сверху и снизу, называется ограниченным.`

Элемент $a \in X$ называется наибольшим или максимальным (наименьшим или минимальным) элементом множества $X \subset \R$, если $x<a$ (соответственно, $a<x$) для любого элемента $x \in X$.

$max(X) := a \in X \wedge \forall x \in X (x \leq a)$

$min(X) := a \in X \wedge \forall x \in X (a \leq x)$

$
sup(X) = s \iff 
\begin{cases}
    \forall x \in X: x \leq S\\
    \forall \epsilon > 0 \quad \exist x \in X : x > S - \epsilon
\end{cases} \iff
\begin{cases}
    \forall x \in X: x \leq S\\
    \forall x < S \quad \exist y \in X: y < x  
\end{cases}
$

$
inf(X) = s \iff 
\begin{cases}
    \forall x \in X: S \leq x\\
    \forall \epsilon > 0 \quad \exist x \in X : x <S + \epsilon
\end{cases} \iff
\begin{cases}
    \forall x \in X: S \leq x\\
    \forall x > S \quad \exist y \in X: y > x  
\end{cases}
$

$sup⁡(X)≔min⁡ \{c \in \R | \forall x \in X (x \leq c)\}$

$inf⁡(X)≔max⁡\{c \in \R | \forall x \in X (c \leq x)\}$


## Свойство


$sup⁡(X_1+ \dots + X_n) =sup(⁡X_1)+ \dots +sup⁡(X_n)$

$inf⁡(X_1+ \dots +X_n)= inf⁡(X_1)+ \dots +inf⁡(X_n)\$


$if \quad \lambda >0, \quad then\\
\qquad sup(\lambda \cdot X) = \lambda \cdot sup(X)\\
\qquad inf(\lambda \cdot X) = \lambda \cdot inf(X)\\
end
$

$if \quad \lambda < 0, \quad then\\
\qquad sup(\lambda \cdot X) = \lambda \cdot inf(X)\\
\qquad inf(\lambda \cdot X) = \lambda \cdot sup(X)\\
end
$

$sup(⁡−X)=−inf⁡X \\ inf(⁡−X)=−sup(⁡X)$

$sup⁡(X−Y)=sup⁡(X)−inf⁡(Y)$
