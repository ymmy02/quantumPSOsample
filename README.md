# Simple Particle Swarm Optimization Sample

Langage : Python

## Abstract

### Purpose

Optimize following function :
```math
F(x_1,x2) = {x_1}^2 + {x_2}^2, S_0 = {(x_1, x_2)| |x_1| \le 5, |x_2| \le 5}
```
### Update Rule

```math
x^i_j(n + 1) = p^i_j \pm \alpha |mbest_j - x^i_j(n)| \times ln(\frac{1}{u})
where
u ~ U(0, 1)
p^i_j = \beta Pbest_j + (1 - \bate) Lbest_j
mbest_j = \frac{1}{N} \sum_{i=1}{N} Pbest^i_j
```

### Graph Structure

Complete Graph

