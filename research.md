---
layout: page
title: Research
permalink: /research/
hide_title: true
---

## Research Goals

The Research in Embodied AI (R.E.A.I) group's mission is to develop embodied intelligent agents capable of solving tasks that benefit humans. We accomplish this primarily through simulation and sim2real transfer, with a focus on minimizing—though not eliminating—real world robot data.

### Cross-Embodiment Policies

We're building towards **one policy to rule them all**: a single unified policy for planning, perception, and control across multiple robotic platforms, including:
- Humanoids
- Bimanual mobile platforms
- Quadrupeds

### Modular Architecture

Our approach decouples the three critical components of embodied intelligence:

1. **Low-Level Control** - Developing a low-level motion control policy
2. **Perception** - Vision models coupled with proprioception
3. **Planning** - Language model-driven task planning

### Learning Pipeline

We're developing new architectures that enable end-to-end learning, building upon the state of the art in robot learning:

**Webscale Pretraining → Robot Data Pretraining → Task Fine-tuning → RL**

## Current Research Projects

### 1. Full-Body Humanoid Teleoperation

Building a full-body humanoid teleoperation system using Meta Quest 3 for high-quality dataset collection. This creates the foundation for learning human-like manipulation and locomotion behaviors.

### 2. Cross-Embodied Motion Control Policy

Developing a cross-embodied adversarial skill embedding style low-level motion control policy for robust sim2real transfer. This project works in tandem with the teleoperation system to enable skills learned in simulation to transfer seamlessly to real-world robots across different embodiments.

### 3. Vision-Language-Action Model

Creating a vision/video language action model with an action expert component that produces embeddings to drive the low-level motion control policy. This bridges high-level perception and language understanding with low-level motor control.
