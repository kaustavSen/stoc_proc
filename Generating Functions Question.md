#### Introduction to Probability Theory and its Applications 

##### Feller Vol. 1 (Page 284, Question 2)

------

##### (a.) 

$$
\begin{align*}
G(s) = \sum_{k=0}^\infty{a_k}s^k &= P(X \leq 0)s^0 + P(X \leq 1)s^1 + P(X \leq 2)s^2 + ...\\
&=p_0 + (p_0+p_1)s + (p_0+p_1+p_2)s^2 + ...\\
&= p_0(1+s+s^2+...) + p_1(s+s^2+...)+...\\
&=(1-s)^{-1}P(s)
\end{align*}
$$

##### (b.)

$$
\begin {align*}
G(s) = \sum_{k=0}^\infty{a_k}s^k &= P(X < 0)s^0 + P(X < 1)s^1 + P(X < 2)s^2 + ...\\
&=p_0(s+s^2+...)+p_1(s^2+s^3+...)+...\\
&=\frac{s}{1-s}P(s)
\end {align*}
$$

##### (c.)

$$
\begin {align*}
G(s) = \sum_{k=0}^\infty{a_k}s^k &= P(X \geq 0)s^0 + P(X \geq 1)s^1 + P(X \geq 2)s^2 + ...\\
&=\{1-P(X <0) \}s^0 + \{1-P(X<1) \}s^1 + \{1-P(X<2) \}s^2+...\\
&=1 + (1-p_0)s + (1-p_0-p_1)s^2 + ...\\
&=\frac{1-sP(s)}{1-s}
\end{align*}
$$

##### (d.)

$$
<Empty \space Math \space Block>
$$





