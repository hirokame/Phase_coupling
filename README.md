# Phase coupling model

位相結合振動子の振る舞いをシミュレーションしてみる。
以下の式を計算。

$\dfrac{d\phi_{i}}{dt}=\omega_{i}+\displaystyle \sum_{j\neq i}^N J_{ij}\sin (\phi_{j}-\phi_{i}+\beta_{ij})$\
$J_{ij}=|C_{ij}|, \beta_{ij}=argC_{ij}, C_{ij}= \displaystyle \sum_{\mu=1}^{P} e^{i(\theta_{i}^{\mu}-\theta_{j}^{\mu})}$\
$\phi_{i}$:細胞iの位相(振動子としての)。$\phi_{i}= \theta_{i}^{\mu}+const$である。\
$\omega_{i}$:細胞iの振動周期(全て同じor狭い幅での分布で与える)\
$C_{ij}$:全てのパターン$\mu \in P$において、細胞iとjの位相差に相当する複素指数関数$e^{i(\theta_{i}^{\mu}-\theta_{j}^{\mu})}$を足し合わせたもの。\
$J_{ij}$:細胞iとjの相互作用パラメター。$C_{ij}$の複素座標上での絶対値。\
$\beta_{ij}$:細胞iとjの位相結合バイアス的なもの？$C_{ij}$の偏角。
