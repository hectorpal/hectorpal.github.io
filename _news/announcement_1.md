---
layout: post
date: 2023-09-21
inline: true
related_posts: false
---

# _"Egocentric Planning for Scalable Embodied Task Achievement"_ accepted at NeurIPS 2023

Joint work with Xiaotian Liu (University of Toronto) and <a href="https://haz.ca">Christian Muise (Queen's University)</a>.

***

_Abstract_: Embodied agents face significant challenges when tasked with performing actions in diverse environments, particularly in generalizing across object types and executing suitable actions to accomplish tasks. Furthermore, agents should exhibit robustness, minimizing the execution of illegal actions. In this work, we present Egocentric Planning, an innovative approach that combines symbolic planning and Object-oriented POMDPs to solve tasks in complex environments, harnessing existing models for visual perception and natural language processing. We evaluated our approach in ALFRED, a simulated environment designed for domestic tasks, and demonstrated its high scalability, achieving an impressive 36.07\% unseen success rate in the ALFRED benchmark and winning the ALFRED challenge at CVPR Embodied AI workshop. Our method requires reliable perception and the specification or learning of a symbolic description of the preconditions and effects of the agent's actions, as well as what object types reveal information about others. It is capable of naturally scaling to solve new tasks beyond ALFRED, as long as they can be solved using the available skills. This work offers a solid baseline for studying end-to-end and hybrid methods that aim to generalize to new tasks, including recent approaches relying on LLMs, but often struggle to scale to long sequences of actions or produce robust plans for novel tasks.

***

Preprint: <a href="https://arxiv.org/abs/2306.01295">https://arxiv.org/abs/2306.01295</a>