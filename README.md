# Life in the Universe — ASTR 120 JupyterBook

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by/4.0/)
[![Jupyter Book](https://img.shields.io/badge/Built%20with-Jupyter%20Book-blue)](https://jupyterbook.org/)
[![Release](https://img.shields.io/badge/release-v1.0.0-green)](https://github.com/saturnaxis/LifeInTheUniverse/releases)

This repository contains the student-facing JupyterBook course reader, study resources, and optional computational activities for **ASTR 120: Life in the Universe** at [East Texas A&M University](https://www.etamu.edu/physics/).

**Live book:** https://saturnaxis.github.io/LifeInTheUniverse/

The course explores one of the largest scientific questions we can ask:

> Are we alone in the universe?

The goal of this book is not to prove that life exists elsewhere. Instead, it teaches students how scientists approach that question using evidence from astronomy, planetary science, biology, chemistry, geology, physics, and computer science.

This book is designed as a guided, evidence-centered course reader rather than a traditional textbook. It blends clear narrative explanations, historical context, figures, videos, checkpoint questions, simple quantitative estimates, optional Python examples, and AI-supported study workflows.

The central theme is that scientific claims require evidence. Evidence does not prove a claim with perfect certainty, but it changes how confident we should be.

---

## Source basis and acknowledgment

This JupyterBook was developed from my ASTR 120 course lecture notes and slide materials, which were originally organized around *Life in the Universe*, 5th edition, by Bennett et al.

The JupyterBook expands those course notes into a student-facing digital reader with additional narrative explanations, figures, videos, checkpoints, course-specific framing, and optional computational examples.

This project is not an official publisher resource and should not be treated as a replacement for the textbook where the textbook is required by the course.

---

## Course focus

*Life in the Universe* introduces students to astrobiology: the scientific study of life in a cosmic context.

Major course themes include:

- what life is and why defining it is difficult,
- how science separates evidence from speculation,
- why Earth is the only confirmed inhabited world so far,
- how astronomy changed humanity’s view of Earth’s place in the universe,
- why planets, moons, stars, chemistry, and energy matter for habitability,
- where life might exist in the Solar System,
- how exoplanets are detected and studied,
- what biosignatures are and why they are difficult to interpret,
- how SETI searches for technological life,
- and why null results can still be scientifically meaningful.

The course treats popular ideas about aliens carefully. Science fiction, UFO claims, and cultural speculation can be useful starting points for discussion, but they are not substitutes for testable evidence.

---

## How to use this book

### For students

Use this book actively. Read the explanations, pause at checkpoint questions, look carefully at figures, and ask how each claim is supported by evidence.

A useful way to study is to ask:

1. What claim is being made?
2. What evidence supports that claim?
3. What alternative explanations are possible?
4. What additional evidence would make the claim stronger or weaker?

Some sections include simple calculations or optional Python examples. These are included to help you understand scale, distance, time, probability, detectability, or habitability. They are not meant to turn the course into a programming course.

Students may use NotebookLM or other AI tools as study aids. Good uses include summarizing sections, generating practice questions, explaining vocabulary, comparing ideas, and checking understanding. AI should support learning, not replace it.

### For instructors

The material is modular and can be adapted for:

- introductory astronomy courses,
- astrobiology courses,
- science-for-nonmajors courses,
- interdisciplinary general education courses,
- or courses using AI-supported reading and revision workflows.

The chapters are built from lecture-slide content, then expanded into narrative prose with figures, videos, checkpoint questions, and simple quantitative examples. The goal is to create a coherent course reader rather than a slide transcript.

---

## Quantitative and computational tools

Mathematics is used lightly throughout the book to build scientific intuition. Most calculations involve ratios, unit conversions, scale comparisons, light travel time, distances, simple probability, or basic graph interpretation.

Python examples are optional enrichment activities. When Python appears, it is usually used as a simple calculator, plotting tool, or way to explore how changing one value changes a result.

Common libraries may include:

- `numpy`
- `matplotlib`

The code is intentionally short and heavily commented. The goal is to help students connect numbers to scientific ideas, not to require prior programming experience.

---

## AI and NotebookLM

This course encourages responsible use of AI as a study partner.

Students may use AI tools to:

- summarize course sections,
- explain difficult vocabulary,
- generate review questions,
- compare scientific ideas,
- clarify figures or examples,
- and receive feedback on their own understanding.

A good AI prompt usually includes:

1. **Persona** — the role the AI should take.
2. **Context** — what the student is studying and what they already know.
3. **Task** — what the student wants the AI to do.

Example:

> Act as a patient introductory astronomy tutor. I am an ASTR 120 student learning about habitable zones for the first time. Explain what a habitable zone is, why it does not guarantee that life exists, and give me three checkpoint questions to test my understanding.

NotebookLM is especially useful because students can add course notes as sources and ask questions grounded in those notes.

AI-generated explanations should always be checked against the course notes, class discussion, and reliable scientific sources.

---

## Repository structure

The repository includes chapter folders, preamble material, static assets, build configuration files, and rendered documentation files.

Typical components include:

- `Chapter01/`, `Chapter02/`, etc. — chapter source materials
- `Preamble/` — course introduction and study guidance
- `_static/` — images, styles, and supporting assets
- `_config.yml` — JupyterBook configuration
- `_toc.yml` — table of contents
- `environment.yml` — environment file for building or working with the book
- `docs/` — rendered GitHub Pages output, when included

---

## Building the book

This repository is built with [Jupyter Book](https://jupyterbook.org/). The book uses MyST Markdown and Jupyter notebooks.

To build locally, install the required environment and run:

```bash
jupyter-book build .
```

Depending on your setup, you may instead build inside the project environment specified by `environment.yml`.

---

## Citation and reuse

This work is licensed under a **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

You are free to:

- **Share** — copy and redistribute the material
- **Adapt** — remix, transform, and build upon the material

provided that appropriate credit is given.

Suggested attribution:

> Quarles, B. *Life in the Universe: ASTR 120 JupyterBook*. East Texas A&M University. Available at https://saturnaxis.github.io/LifeInTheUniverse/

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
