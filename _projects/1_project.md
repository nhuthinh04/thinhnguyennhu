---
layout: page
title: Inverse Design of Kresling Origami via PINNs
description: Modeling and multi-solution inverse design of Kresling origami structures using Physics-Informed Neural Networks.
img: assets/img/12.jpg
importance: 1
category: Research
related_publications: true
---

This project investigates Physics-Informed Machine Learning (PIML) methods for the structural modeling and inverse design of Kresling origami structures.

### Background & Motivation
Kresling origami is a cylindrical origami pattern that exhibits coupled axial and rotational motions with tunable bistability and multistability. Designing such metamaterials with pre-programmed mechanical characteristics typically involves solving complex non-linear inverse problems with multiple possible geometries.

### Key Highlights
- **Neural Surrogate Modeling:** Developed high-fidelity neural surrogate models capable of predicting mechanical load-displacement responses rapidly without costly numerical simulations.
- **Physics-Informed Loss Formulation:** Formulated custom loss functions embedding kinematic constraints, equilibrium equations, and elastic strain energy.
- **Multi-Solution Inverse Design:** Enabled effective inverse parameter identification to discover optimal structural parameters fulfilling target stiffness, bistability, and energy absorption profiles.

Check out our related papers: {% cite vuong2026gradient %} and {% cite nguyen2025dynamic %}.
