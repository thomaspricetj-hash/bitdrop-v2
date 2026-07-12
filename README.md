# BitDrop V2 — Reversible 32‑Bit Collapse Compressor (Rust)

BitDrop V2 is a high‑performance, Rust‑based compression engine built around a fully reversible 32‑bit collapse system. It performs multi‑pass reduction, entropy‑aware routing, and structural pattern detection to achieve dense, deterministic compression while preserving perfect reversibility.

BitDrop is **source‑available for evaluation**, allowing developers to inspect, test, benchmark, and experiment with the compressor.  
**Commercial use requires a paid license.**

---

## Features

- **Reversible 32‑bit collapse engine**  
  Every reduction step is tagged, traceable, and fully reversible.

- **Multi‑pass compression pipeline**  
  Each pass refines entropy thresholds, collapse ordering, and structural alignment.

- **Entropy‑aware routing**  
  Bloom‑filter‑based rule selection accelerates collapse operations.

- **Deterministic output**  
  Same input → same collapse map → same compressed result.

- **Rust performance + safety**  
  Zero‑cost abstractions, memory‑safe rule execution, and predictable behavior.

- **Self‑analysis metadata**  
  Each run produces collapse statistics, entropy maps, and rule usage metrics.

---

## Evaluation License

BitDrop V2 is released under the **BitDrop Compressor Evaluation License (Non‑Commercial)**.

You may:
- download the source  
- compile the compressor  
- run benchmarks  
- test integration  
- perform research and evaluation  

You may **not**:
- use BitDrop in commercial or production systems  
- redistribute or sublicense the code  
- publish modified versions  
- integrate BitDrop into closed‑source or revenue‑generating software  

For commercial licensing, contact:  
**GitHub: thomaspricetj-hash**

---

## Building

Ensure Rust is installed:

```bash
rustup update
