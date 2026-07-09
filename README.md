# Attention-Driven-Interrupt-Firmware
A Biologically-Grounded Architecture for Artificial Intelligence

### Research Paper
Read our full preprint on Zenodo:
👉 [Attention-Driven Interrupt Firmware: A Biologically-Grounded Architecture for Artificial Intelligence](https://zenodo.org/records/20508617)

---

## Abstract Summary

Current Large Language Models (LLMs) are built on the Universal Approximation Theorem (UAT), which guarantees that neural networks can approximate any continuous function to arbitrary precision. However, this foundation is structurally misaligned with discrete, non-continuous formal logic problems, leading to high energy consumption and superficial reasoning.

The **Attention-Driven Interrupt Firmware (ADIF)** architecture resolves this misalignment by utilizing a **typed, learnable lookup table** that simultaneously serves as the system's routing mechanism, knowledge store, and learning substrate.

---

## Architectural Mechanics

Every incoming query passes through a **weight-free classification gate** to determine if it is formal logic or subconscious continuous. It is then dispatched to a dual-path routing mechanism:

* **Formal Logic Path (Discrete):** Logic-labeled entries use **Reduced Ordered Binary Decision Diagrams (ROBDDs)** for exact canonical matching.
* **Subconscious Continuous Path:** Subconscious-labeled entries use **fastText semantic vector cosine similarity**.
* **Attention Path (Fallback):** Queries with no sufficiently close match trigger the attention path as a last resort.

This unified design eliminates the need for a separate routing classifier, enables explicit learnability through table growth, and grounds the architecture in the biological principle that stimulus routing is a form of accumulated structured knowledge. The result is an AI framework that is slimmer, more stable, and inherently energy-efficient.

---

## Keywords
`ADIF` • `Attention-Driven Interrupt Firmware` • `Universal Approximation Theorem` • `Formal Logic` • `von Neumann Bottleneck` • `Overhead-Free Learnability` • `Typed Lookup Table` • `Reduced Ordered Binary Decision Diagrams` • `Weight-Free Dispatch` • `Subconsciousness` • `Energy Efficiency` • `Biologically-Grounded AI`


















## Paper citation:
```bibtex
@article{tang2026attention,
  author    = {Tang, Yungui},
  title     = {Attention-Driven Interrupt Firmware: A Biologically-Grounded Architecture for Artificial Intelligence},
  journal   = {Zenodo Preprint},
  year      = {2026},
  doi       = {10.5281/zenodo.20508617},
  url       = {https://zenodo.org}
}
```
