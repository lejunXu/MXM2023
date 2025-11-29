# Tangled Labelings on Posets

**Research Project | Fall 2023** **Madison Experimental Mathematics Lab (MXM), UW-Madison**

## 📄 Overview
This repository contains the research materials (final report and poster) for the project **"Tangled Labelings on Posets"**. This research was conducted under the supervision of the Madison Experimental Mathematics Lab (MXM).

Our work investigates the dynamical properties of the **Promotion Algorithm** on finite partially ordered sets (posets), focusing on the combinatorial structure of "Tangled Labelings."

## 📂 Files
* **[`MXM_2023.pdf`](./MXM_2023.pdf)**: The comprehensive technical report detailing definitions, proofs, and the demotion algorithm.
* **[`MXM_Fall_2023_Posets__Copy_.pdf`](./MXM_Fall_2023_Posets__Copy_.pdf)**: The research poster presented at the MXM end-of-semester visualization symposium.

## 🧮 Research Summary
**Background:** The **Promotion Algorithm** ($\partial$) is a bijection on the set of linear extensions (labelings) of a poset. It is known that repeatedly applying promotion eventually transforms any labeling into a "natural labeling" (linear extension consistent with the poset order).

**Problem Statement:** We studied **Tangled Labelings**, defined as labelings that require the maximum possible number of promotion steps ($n-1$) to become natural. Our primary goal was to investigate the conjecture that any $n$-element poset has at most $(n-1)!$ tangled labelings.

**Key Contributions:**
* **Inverse Analysis (Demotion):** Developed and formalized **"Demotion Algorithms"** ($\partial^{-1}$, including "Cold" and "Maximal" variants) to generate preimages of natural labelings and systematically find tangled labelings.
* **Theoretical Bounds:** Proved that for any poset with a unique minimal element, the number of tangled labelings is exactly $(n-1)!$.
* **Ambidextrous Labelings:** Introduced the concept of "Ambidextrous Labelings" to analyze posets with two minimal elements.
* **Computational Verification:** Implemented the promotion/demotion algorithms in Python to simulate orbit structures and verify conjectures for small $n$.

## 👥 Contributors
* **Lejun Xu**
* Lucas Allen
* Zachary George
* Harris Liu

**Mentors:**
* Prof. Paul Terwilliger
* Owen Goff (Graduate Mentor)

## 📚 References
1.  C. Defant and N. Kravitz, *Promotion Sorting*, Order 58 (2022), 1-18. arXiv:2005.07187.
2.  M. Haiman, *Dual equivalence with applications*, J. Algebraic Combin. 1 (1992), 305–327.
