# The divisible sandpile odometer at the critical lower tail

Yitzchak Shmalo

The paper (`main.tex`, `main.pdf`) treats the endpoint gamma = d/2 that is excluded in Theorem 1.3(iii)(b) of A. Bou-Rabee and C. Panagiotis, *Quantitative explosion and percolation of the divisible sandpile* (arXiv:2609.02829).

Let d >= 5 and let P be the transition operator of simple random walk on Z^d. For i.i.d. centered scenery eta, the synchronous odometer is

    u_0 = 0,   u_{n+1} = (eta + P u_n)_+ .

If eta has an absolute exponential moment and

    exp(-C t^(d/2)) <= P(eta(0) < -t) <= exp(-c t^(d/2))   for large t,

then

    E u_n(0) is of order (log n)^(2/d) (log log n)^(1 - 2/d).

The log-log factor comes from the logarithmic divergence of the sum of G(0,y)^(d/(d-2)) over a ball, where G is the Green function. The lower bound uses the exact discrete supersolution a log(1 + |x|^2) together with the Harris-FKG inequality for its boundary conditions.

The paper also proves that a negative tail of order exp(-t^gamma) with 0 < gamma < 1, together with an exponential positive tail, gives E u_n(0) of order (log n)^(1/gamma), without an absolute exponential moment.

The paper is part of the Math Brain project: https://github.com/yspennstate/math-brain-public

## Files

- `main.tex`: LaTeX source (amsart)
- `main.pdf`: compiled paper, 12 pages
