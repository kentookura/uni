66) Let $(a_n), (b_n) \in V$ and $(a)$. Then
a) \begin{gather}
     \varphi(a) + \varphi(b) = (0, a_1 + b_1, a_2 + b_2, ...) = \varphi(a+b)\\
     \alpha \cdot \varphi(a) = (0, \alpha \cdot a_1, \alpha \cdot a_2, ...) = \varphi(\alpha \cdot a)\\
     \psi(a) + \psi(b) = (a_2 + b_1, ...) = \psi(a+b)\\
     \alpha \cdot \psi(a) = (\alpha \cdot a_2, \alpha \cdot a_3...) = \psi(\alpha \cdot a)\\
     \varphi(0) = 0, \quad \psi(0) = 0
   \end{gather}
b) \begin{gather}
   \psi(\varphi(a)) = a
   \end{gather}  
   So $\psi$ is left-inverse to $\varphi$ but $(1, 0, 0, ...)$ for instance is not in the image of $\varphi$.
c) $\psi(\varphi(a)) = (a_1, a_2, ...)$ but $\phi((x, a_1, a_2,..) = a$ for $x \in \mathbb{R}$, so preimages are not unique.

67) a)
    $(\gamma \circ \varphi)(a) = 0$  if $\gamma((a_1, a_2,...) = (a_1, 0, 0, ...)$ but  
    $$(\varphi \circ \gamma)(a) = 0 \iff \gamma = 0 \in R$$
    b)
    $(\psi \circ \gamma)(a) = 0$ for any $\gamma$ whose image is contained in $\{(x, 0, 0,), x \in \mathbb{R}\}$,
    for instance $\gamma((a_n)) = (a_1, 0, 0,..)$, but  
    $$(\gamma \circ \psi)(a) = 0 \iff \gamma(a) = 0, \quad \forall a \in V$$

68) a)
    Let $R = \{a/p^n \rvert a, n \in \mathbb{Z}\}$. Then $a/p^n + b/p^m = \frac{(ap^m+bp^n)}{p^{n+m}} \in R$  
    and $a/p^n \cdot b/p^m = \frac{ab}{p^{n+m}} \in R$  
    It is an not an ideal. Take $\frac{1}{2} \in R = \{\frac{a}{2^n}\}$. Then $\frac{1}{3} \cdot \frac{1}{2} = \frac{1}{2 \cdot 3} \notin R$
    b)
    If $p \nmid a,\, p \nmid b$, then $p \nmid ab$  
    Let $R = \{a/b \,\rvert\, a,b \in \mathbb{Z},\, p \nmid b\},\quad \alpha, \beta \in R$  
    Then
    $\alpha + \beta = \frac{a}{b} + \frac{d}{c} = \frac{ac + db}{bc}$ and $\alpha \cdot \beta = \frac{ad}{bc}$, 
    which are both elements of $R$.
    It is not an ideal.
69) a) Let $a = (a_1,...,a_n), b = (b_1,...,b_n) \in S = S_1 \times \cdots \times S_n$.  
       Then $a + b = (a_1,...,a_n) + (b_1,...,b_n) = (a_1 + b_1,...,a_n + b_n)$ in $S$
       and $ab = (a_1b_1,...,a_nb_n)$ in $S$
    b) We only need to prove $ab \in I = I_1 \times \cdots \times I_n$, where $a \in R, b \in S$
       $ab = (a_1b_1,...,a_nb_n)$ and we know that $a_ib_i \in I_i$. Thus $I$ is an ideal
70) a) Let $a, b \in Z(R)$. Then $x (a+b) = xa + xb = ax + bx = (a+b) x$ and $abx = axb = xab$
    b) Let $a = (a_1,...,a_n) \in Z(R_1 \times \cdots \times R_n)$. By definition, each $a_i$ 
       commutes with every element of $R_i$, so  
       $$Z(R_1 \times \cdots \times R_n) \in Z(R_1)\times \cdots \times Z(R_n)$$
       For the other direction let $a \in Z(R_1)\times \cdots \times Z(R_n)$.
       Since each $a_i$ commutes with elements from $R_i$, $a$ commutes with every element from $R_1 \times \cdots \times R_n$
       

