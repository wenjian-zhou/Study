# Chapter 1

## 1.3 The Axiom of Completeness

*Every nonempty set of real numbers that is bounded above has a least upper bound.*

> Why there is no need to assert that greatest lower bounds exist as part of the Axiom of Completeness?

Let $A$ be nonempty and bounded below, and define $B=\{b \in R: b\text{ is a lower bound for } A\}$. Then $\sup B = \inf A$, proves the greatest lower bound exists using the least upper bound.

**Lemma**: Assume $s \in R$ is an upper bound for a set $A \subseteq R$. Then, $s = \sup A$ if and only if, for every choice of $\epsilon > 0$, there exists an element $a \in A$ satisfying $s - \epsilon < a$.

## 1.4 Consequences of Completeness

**Theorem**(Nested Interval Property): For each $n \in N$, assume we are given a closed interval $I_n = [a_n, b_n] = \{x \in R : a_n \leq x \leq b_n\}$. Assume also that each $I_n$ contains $I_{n+1}$. Then, the resulting nested sequence of closed intervals

$$
I_1 \supseteq I_2 \supseteq I_3 \supseteq I_4 \supseteq \dots
$$

has a nonempty intersection; that is, $\bigcap^{\infty}_{n=1}I_n \neq \emptyset$.

Proof: Use Axiom of Completeness to produce $x = \sup A$, prove $a_n \leq x$ and $x \leq b_n$.

### The Density of $Q$ in $R$

**Theorem**(Archimedean Property): 

1. Given any number $x \in R$, there exists an $n \in N$ satisfying $n > x$.
2. Given any real number $y > 0$, there exists an $n \in N$ satisfying $1/n < y$.

Proof: Part 1 $\Rightarrow$ $N$ is not bounded above. So assume $N$ is bounded above.

**Theorem**(Density of $Q$ in $R$): For every two real numbers $a$ and $b$ with $a < b$, there exists a rational number $r$ satisfying $a < r < b$.

**Corollary**: Given any two real numbers $a < b$, there exists an irrational number $t$ satisfying $a < t < b$.