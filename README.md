# CS336: Language Modeling from Scratch 

## Intent

Documenting Stanford's CS336's run. The course builds a complete language model pipeline from scratch — tokenizer, architecture, training, scaling, systems — and the goal here is the same as CS231n: **derivation-level understanding**, with working PyTorch implementations


## Course resources

- Course site: [cs336.stanford.edu](https://cs336.stanford.edu/)
- Lecture repo (Percy Liang, official code): [stanford-cs336 GitHub org](https://github.com/stanford-cs336)
- Lecture videos (Spring 2025 / 2026): [YouTube — Stanford CS336](https://www.youtube.com/results?search_query=stanford+cs336+language+modeling+from+scratch)

## Repo structure

```
cs336/
├── assignment1-basics/        (tokenizer, transformer architecture, training loop)
├── assignment2-systems/       (GPU kernels, Triton, parallelism)
├── assignment3-scaling/       (scaling laws, hyperparameter prediction)
├── assignment4-data/          (data pipelines, filtering)
├── assignment5-alignment/     (SFT, RLHF-style alignment)
├── lectures/                  (official lecture code, if pulled in)
├── notes/                     (derivations, conceptual notes)
└── README.md
```

## Progress tracker

### Lectures

| # | Topic | Status |
|---|---|---|
| 1 | Overview, Tokenization | ⬜ Not started |
| 2 | PyTorch, resource accounting | ⬜ Not started |
| 3 | Architectures, hyperparameters | ⬜ Not started |
| 4 | Mixture of experts | ⬜ Not started |
| 5 | GPUs | ⬜ Not started |
| 6 | Kernels, Triton | ⬜ Not started |
| 7 | Parallelism 1 | ⬜ Not started |
| 8 | Parallelism 2 | ⬜ Not started |
| 9 | Scaling laws 1 | ⬜ Not started |
| 10 | Inference | ⬜ Not started |
| 11 | Scaling laws 2 | ⬜ Not started |
| 12 | Evaluation | ⬜ Not started |
| 13–14 | Data 1 & 2 | ⬜ Not started |
| — | Alignment (SFT / RLHF) | ⬜ Not started |

### Assignments

| Assignment | Status | Notes |
|---|---|---|
| A1 — Basics (tokenizer, transformer, training) | ⬜ Not started | |
| A2 — Systems (kernels, parallelism) | ⬜ Not started | |
| A3 — Scaling | ⬜ Not started | |
| A4 — Data | ⬜ Not started | |
| A5 — Alignment | ⬜ Not started | |

> Status legend: ✅ Done · 🔄 In progress · ⬜ Not started

## Notes on scope

- Heavily implementation-focused course by design — expect most of the value to be in code, not slides.
- Builds directly on CS231n foundations (backprop, optimization) and feeds into multimodal/frontier work — kept as a separate repo from CS231n since the syllabus and pace differ.
- Prerequisites assumed by the course (per official site): linear algebra, basic probability/stats, and ML fundamentals — covered by CS231n + [LinearAlgebra18.06](#) repos.
