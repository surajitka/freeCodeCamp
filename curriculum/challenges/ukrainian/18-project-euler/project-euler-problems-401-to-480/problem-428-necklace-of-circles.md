---
id: 5900f5191000cf542c51002b
title: 'Problem 428: Necklace of Circles'
challengeType: 1
forumTopicId: 302098
dashedName: problem-428-necklace-of-circles
---

# --description--

Нехай $a$, $b$ та $c$ будуть додатними числами.

Нехай $W$, $X$, $Y$, $Z$ будуть чотирма колінеарними точками, де $|WX| = a$, $|XY| = b$, $|YZ| = c$ та $|WZ| = a + b + c$.

Нехай $C_{\text{in}}$ буде колом з діаметром $XY$.

Нехай $C_{\text{out}}$ буде колом з діаметром $WZ$.

The triplet ($a$, $b$, $c$) is called a *necklace triplet* if you can place $k ≥ 3$ distinct circles $C_1, C_2, \ldots, C_k$ such that:

- $C_i$ has no common interior points with any $C_j$ for $1 ≤ i$, $j ≤ k$ and $i ≠ j$,
- $C_i$ is tangent to both $C_{\text{in}}$ and $C_{\text{out}}$ for $1 ≤ i ≤ k$,
- $C_i$ is tangent to $C_{i + 1}$ for $1 ≤ i &lt; k$, and
- $C_k$ is tangent to $C_1$.

For example, (5, 5, 5) and (4, 3, 21) are necklace triplets, while it can be shown that (2, 2, 5) is not.

<img class="img-responsive center-block" alt="a visual representation of a necklace triplet" src="https://cdn.freecodecamp.org/curriculum/project-euler/necklace-of-circles.png" style="background-color: white; padding: 10px;" />

Let $T(n)$ be the number of necklace triplets $(a, b, c)$ such that $a$, $b$ and $c$ are positive integers, and $b ≤ n$. Наприклад, $T(1) = 9$, $T(20) = 732$ та $T(3\\,000) = 438\\,106$.

Знайдіть $T(1\\,000\\,000\\,000)$.

# --hints--

`necklace(1000000000)` має повернути `747215561862`.

```js
assert.strictEqual(necklace(1000000000), 747215561862);
```

# --seed--

## --seed-contents--

```js
function necklace(n) {

  return true;
}

necklace(1000000000)
```

# --solutions--

```js
// solution required
```
