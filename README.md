# NTT for Cyclotomic Trinomials

Reference Jupyter notebook (`ntt_trinomial.ipynb`) for mixed Radix-2 / Radix-3 NTT over cyclotomic trinomial rings, as used in NTRU+.

Rq = Z_q[x]/(x^n - x^{n/2} + 1),  n = 2^a 3^b

This notebook provides primitive root selection, zeta table generation, and explicit mixed-radix index layouts used by forward and inverse NTT layers in reference and optimized implementations.  

---
