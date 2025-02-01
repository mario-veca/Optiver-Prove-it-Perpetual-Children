# Optiver Prove It - Perpetual Children
(**Last Updated**: February 1, 2025)

This repository contains my solution to the **Optiver Prove It: Perpetual Children** challenge, a probability problem 
exploring **random walks and recurrence relations**.  
The goal is to **prove that a child generation process will always eventually terminate**, even though the **expected 
number of children (or time to termination) is infinite**.

Despite its simple rules, solving this problem requires a solid understanding of **stochastic processes, recurrence 
relations, and random walks with absorbing states**.  
This solution rigorously derives a recurrence equation for the probability of eventual stop, solves it analytically,
and **proves that the process eventually stop with probability equal to 1**.

The original problem can be found on the [Optiver Prove It challenge page](https://optiver.com/prove-it-5/).

---

## 📖 Problem Statement
Each couple follows these rules:
- They start by having a **first child**.
- They continue to have children **until the number of boys and girls is equal**.
- Each child is **independently male or female** with probability **1/2**.

The goal is to **prove that this process always terminates**, even though the expected number of children is infinite.

---

## 📝 Solution Approach
This problem can be analyzed using **stochastic processes** and is closely related to the **gambler’s ruin problem**.  
In my solution:
- I model the process as a **random walk with an absorbing state**.
- I derive a **recurrence relation** for the probability of eventual termination.
- I **prove rigorously** that the process must always end.

The full proof is provided in the **[`Perpetual_children.pdf`](./Perpetual_children.pdf)** document.

---

## ⚠️ Disclaimer
This repository presents an **independent solution** to a problem inspired by Optiver.  
The problem formulation originates from Optiver material, but the solution and analysis are **original work by the author**.  
This repository is **not affiliated with or endorsed by Optiver**.

---

## ⚖️ License
This work is licensed under **Creative Commons BY-NC-ND 4.0**.  
You may read and share it, but modifications and commercial use are **not allowed**.  
See [LICENSE](LICENSE) for details.

---
© 2025 Mario Veca
