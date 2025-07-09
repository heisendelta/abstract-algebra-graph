# Visualization of Theorems & Corollaries from an Abstract Algebra course

We created a graph of theorem and corollaries in Fraleigh's "A First Course in Abstract Algebra" with directed edges from theorems/corollaries to the previous theorems/corollarie/examples they reference.

That is, a node with a high *out-degree* indicates a theorem/corollary that references many other theorems/corollaries and a node with a high *in-degree* indicates a theorem/corollary that is highly referenced by other theorems.

The node with the highest *out-degree* is 
> ***Theorem 30.23*** Let $E$ be an extension field of $F$, and let $\alpha \in E$ be algebraic over $F$. If $\text{deg}(\alpha, F) = n$, then $F(\alpha)$ is an $n$-dimensional vector space over $F$ with basis ${1, \alpha, ..., \alpha_{n-1}}$. Furthermore, every element $\beta$ of $F(\alpha)$ is algebraic over $F$, and $\text{deg}(\alpha, F) \le \text{deg}(\alpha, F)$.


The node with the highest *in-degree* is
> ***Theorem 11.12* (Fundamental Theorem of Finitely Generated Abelian Groups)** Every finitely generated abelian group $G$ is isomorphic to a direct product of cyclic groups in the form $\mathbb{Z}_{(p_1)^{r_1}} \times \mathbb{Z}_{(p_2)^{r_2}} \times ... \times \mathbb{Z}_{(p_n)^{r_n}} \times \mathbb{Z} \times \mathbb{Z} \times ... \times \mathbb{Z}$, where the $p_i$ are primes, not necessarily distinct, and the $r_i$ are positive integers. The direct product is unique except for possible rearrangement of the factors; that is, the number (*Betti number* of G) of factors $\mathbb{Z}$ is unique and the prime powers ${p_i}^{r_i}$ are unique.