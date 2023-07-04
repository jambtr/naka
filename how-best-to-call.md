**Example.** $G(O)\subset G(K)$ is parabolic.

Consider $G/B$. There are bijections
<!-- \begin{gather*} -->
$$
W = N_G(T)/T \to B\backslash G/B \to \{B\text{-orbits on } G/B\} \\ \to \{G\text{-diagonal orbits on } G/B \times G/B\}
$$
<!-- \end{gather*} -->
Let $\tilde{\g} := \{(x,b) \in \g\times G/B : x \in b\}$. There are resolutions
<!--$$
% \begin{tikzcd}
    % &\tilde\cN = G\times^B\n \ar[drrr,dashed] \ar[dl,"\mu"']\ar[rr,hook]&&\tilde{\g} = G\times^B\b \ar[dl,"\mu"']\ar[dr,"\pi"]\\
    % \cN\ar[rr,hook]&&\g & & G/B
% \end{tikzcd}
$$-->
such that 

- $\pi^{-1}([\b]) = \b$ such that $\pi : \tilde g\to G/B$ is a vector bundle (in fact, it is a $G$-equivariant bundle isomorphic to $G\times^B\b$) %  \{x: x\in\b\} = % which is a vector space, so
- $\mu^{-1}(x) \cong W$ such that $\mu: \tilde\g^{sr}\to\g^{sr}$ is a principal $W$-bundle % for $x\in \g^{sr}$ 

<!-- - % on $\cN$... (those $x\in\g$ having nilpotent $ad(x)$) -->
<!-- (g,x) \mapsto (gxg^{-1},gB/B) -->
The Steinberg variety 
$$
Z = \tilde\cN\times_{\cN}\tilde\cN = \{((x,b),(x',b')) : x = x'\}
$$
has $H_\bullet(Z) \cong k[W]$ endowing $H_\bullet(G/B)$ with a $W$ action.

As $Z \cong \{(x,\b,b'): x\in\b\cap\b'\}$ we have maps 
<!-- $$
% \begin{tikzcd}
    % & Z  = \bigsqcup_W T^\ast_{O_w}(G/B\times G/B)\subset T^\ast(G/B\times G/B) \ar[dl] \ar[dr]\\
    % \cN && G/B\times G/B
% \end{tikzcd}
$$ -->
where $O_w$ is the $G$-orbit (for the diagonal action) in $G/B \times G/B$.