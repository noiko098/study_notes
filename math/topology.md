# 位相空間 (Topological Space)

## 定義
集合 $X$ と，その部分集合の族 $\mathcal{O}_X$ の組 $(X, \mathcal{O}_X)$ が，次の三条件を満たすとき，これを **位相空間** と呼ぶ。

1. **空集合と全体集合:**
   $\emptyset \in \mathcal{O}_X$ および $X \in \mathcal{O}_X$
2. **有限共通部分:**
   $U, V \in \mathcal{O}_X \implies U \cap V \in \mathcal{O}_X$
3. **任意和集合:**
   $$\{U_\lambda\}_{\lambda \in \Lambda} \subset \mathcal{O}_X \implies \bigcup_{\lambda \in \Lambda} U_\lambda \in \mathcal{O}_X$$

$(X, \mathcal{O}_X)$ が位相空間であるとき， $\mathcal{O}_X$ を $X$ 上の **位相** と呼び， $\mathcal{O}_X$ の元を **開集合** という。
