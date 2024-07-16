
Recordemos que en $\mathbb{R}^3$
$$
\nabla = (Dx,Dy,Dz)
$$

Sea $F:U\subset \mathbb{R}^n\to \mathbb{R}^m$ tal que $F=(f_{1},f_{2},\dots,f_{m})$, con $f_{1},\dots,f_{m}:V\subset \mathbb{R}^n\to \mathbb{R}$
Entonces
$$
rot F = \nabla \times F
$$
Que, en $\mathbb{R}^3$ toma esta forma
$$
\begin{align}
rotF & =\det \begin{pmatrix}
i & j & k \\
Dx & Dy & Dz \\
f_{1} & f_{2} & f_{3}
\end{pmatrix} \\
rotF & =i\cdot(D_{y}f_{3}-D_{z}f_{2})-j\cdot(D_{x}f_{3}-D_{z}f_{1})+k(D_{x}f_{2}-D_{y}f_{1}) \\
rotF & = (D_{y}f_{3}-D_{z}f_{2};D_{z}f_{1}-D_{x}f_{3};D_{x}f_{2}-D_{y}f_{1})
\end{align}
$$
*El rotacional se relaciona con las rotaciones en gases y fluídos.*