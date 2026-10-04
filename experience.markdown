---
layout: page
title: Experience
description: >-
  Research experience of Vincenzo Pomponi: PhD at USI and scientific collaborator
  at the SUPSI ARM Lab, generative robot policies, human–robot collaboration and
  EU-funded projects.
permalink: /experience/
---

<div class="role"><h3>Scientific Collaborator &amp; PhD Candidate</h3><span class="when">2022 – Present</span></div>
<p class="where">SUPSI Automation, Robotics and Machines (ARM) Laboratory / USI — Lugano, Switzerland</p>

## Generative robot policies

- Built **DynaMimicGen**, a DMP-based data generation framework that synthesizes large manipulation datasets from one or two human demonstrations instead of ten. It improves generation success by up to 233% over MimicGen and lifts Diffusion Policy performance (e.g. Square: 75% → 87%), validated in simulation and on a real Franka Emika Panda.
- Developed **DROM**, a language-guided diffusion framework that learns 17 manipulation skills in a single policy and composes them via an LLM task decomposer into long-horizon instructions of up to 9 chained skills, raising average success from 61% to 91% over the Motion Planning Diffusion baseline on a FANUC CRX-25iA and a Franka Research 3.
- Designed personalized DMP trajectories with real-time velocity scaling for collaborative transport of an aircraft engine cowl lip, outperforming an industrial BiTRRT planner in user preference and in physiological stress measures (EEG and skin conductance).
- Benchmarked vision–language–action models (SmolVLA, OpenVLA) for manipulation with state-of-the-art simulation frameworks such as RoboSuite and ManiSkill.

## Vision-based activity recognition for HRC <small>(under review)</small>

- Collected a new multimodal RGB-D dataset of 19 assembly activities for the collaborative assembly of a heavy aircraft component, and adapted a transformer-based few-shot action recognition method to this industrial task.
- Reached 95% recognition accuracy on 24 participants after training on 5 operators (30 trials per activity), showing strong cross-person generalization from limited data.
- Integrated recognition outputs into a Hierarchical Task Network (HTN) planner controlling a FANUC CRX-25iA cobot, enabling the robot to anticipate the operator's next assembly step in real time.

## EU-funded projects & system integration

- Contributed to the Horizon Europe project [Fluently](https://www.fluently-horizonproject.eu/) (22 industrial and academic partners), leading research development, experimentation and system integration for the Dexterity use case, where a robot collaborates with a human during non-expert operator training.
- Integrated learning from demonstration, speed scaling based on human–robot distance, natural-language intent recognition and 6D object pose estimation (FoundationPose) into a complete collaborative robotic cell (FANUC CRX-20iA/L) using ROS 2.
- Presented the system in a live human–robot collaboration demonstration at the project's final General Assembly; supervised 1 MSc student.

---

## Education

<div class="role"><h3>PhD in Informatics</h3><span class="when">2023 – Expected Sep 2027</span></div>
<p class="where">Università della Svizzera italiana (USI), Lugano, Switzerland</p>

- Thesis: diffusion-based generative models for robotic manipulation and human–robot interaction.
- Advisors: Luca Maria Gambardella, Anna Valente, Stefano Baraldo.

<div class="role"><h3>MSc in Mechanical Engineering</h3><span class="when">2016 – 2022</span></div>
<p class="where">Politecnico di Milano, Italy — final grade 106/110</p>

- Thesis: Implementation of Active multi-Preference Learning for a collaborative robot with ergonomics assessment.
- Advisors: [Hamid-Reza Karimi](https://scholar.google.no/citations?user=YcTS0ZMAAAAJ&hl=en) and [Loris Roveda](https://scholar.google.com/citations?user=3un_pPgAAAAJ&hl=en).

---

## Technical skills

- **Machine learning & GenAI:** Python, PyTorch, diffusion models (Diffusion Policy, Implicit Reactive Diffusion Policy), imitation learning, VLAs (OpenVLA, SmolVLA), transformers, preference learning
- **Robotics:** ROS / ROS 2, Dynamic Movement Primitives, manipulation, human–robot collaboration; Franka, FANUC CRX-20iA/L, FANUC CRX-25iA; MuJoCo, Isaac Sim, RoboSuite, RoboMimic, ManiSkill
- **Computer vision:** activity recognition, human pose estimation, RGB-D perception, OpenCV
- **Tools:** Git, Linux, Docker, Weights & Biases, CUDA, GPU cluster training

**Languages:** Italian (native) · English (professional)
