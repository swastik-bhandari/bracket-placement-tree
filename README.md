# Bracket Placement Tree (BPT)

The **Bracket Placement Tree (BPT)** is a novel combinatorial structure developed to model all valid placements of opening brackets in well-formed parentheses sequences. This approach uses an index-based representation and provides a fresh perspective on classical problems involving Catalan numbers and balanced parentheses.

## 📘 Overview

BPT grows level by level, where each level corresponds to the position of the next opening bracket. It maintains valid configurations by enforcing:

- Strictly increasing index order,
- Catalan number-based structural bounds,
- Valid sequence constraints derived from combinatorics.

This framework opens up new possibilities in parsing theory, formal language analysis, and algorithm design.

## 🧠 Key Features

- Enumerates **all valid bracket placements** based on index progression.
- Answers nuanced structural questions like:
  - Given partial bracket positions, how many valid sequences can be completed?
  - What are the valid positions for remaining brackets?
  - How many pairs can be formed given a structure?
- Example:
  > For *n = 4* pairs (length 8), if the first three opening brackets are placed at indices 0, 1, and 4, BPT determines that there are **2** valid completions: **0145** and **0146**.  
  > This is traditionally difficult to compute directly using existing methods.

## 📊 Diagram

A visual diagram illustrating the BPT structure and traversal logic is included in the repository. It aids in understanding the tree's branching and decision flow.

## 🚧 Current Status

This is a **conceptual project** in development. No code is available yet — only the design and analysis model. Future goals include:

- Implementing the BPT construction algorithm,
- Exploring applications in parsing and compiler theory,
- Formalizing the concept into a research paper or collaborative project.

## 📄 License

This repository is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

---

**Author:** Swastik Bhandari  
**Email:** swastik3223@student.ku.edu.np
