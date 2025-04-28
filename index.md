---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

permalink: /
title: Home
longtitle: Explaining Vision and Language Models — A Concept-Based Approach
subtitle: Tutorial @ ECAI 2025
layout: home
toc: false
---

> We need to understand and explain what our models have learned. Concept-based XAI is a step on the way to get there.


In this tutorial, researchers and practitioners of DNNs are invited to learn
which methods from **explainable artificial intelligence (XAI)** are ready at hand
to gain insights into computer vision and language models.
Our technical deep dive will highlight emerging **concept-based explainability** techniques ([C-XAI](https://arxiv.org/abs/2409.13456)),
followed by a practical session including a discussion of participant-contributed use-cases.


## An Overview
With the advances of deep learning, in particular in computer vision and natural
language processing, came the pressing need to make their inner workings more
explainable: Not only do ethical requirements arise in critical areas but better insights
can also help to steer research on how to further improve the models. The resulting
emerging field of explainable AI (XAI) has since introduced a vast range of methods
and tools that can assist with diverse explainability problems—possibly overwhelming
novices and practitioners.
This half-day tutorial aims to lift the curtain, and both provide an **overview on XAI
problems and techniques**, as well as a **practical guide** to method selection, practiced in
a hands-on exploration and discussion part. As a highlight, a special focus will be given
to the emerging field of **concept-based explanations** of latent spaces, as well as future
challenges that could be a starting point for entering the research field. We welcome
both junior researchers as well as experts from areas using or developing DNNs.


### Techniques and Methods Covered
The following explainability methods will be introduced:

+ Ante-hoc explainability techniques: transparent and hybrid models.
+ Post-hoc model distillation: Techniques to approximate (parts of) a trained DNN with an
explainable model.
+ Post-hoc local feature importance methods: These identify features in a given input that have
a high attribution to the DNN output.
+ Concept-based explanations, following [our survey](https://arxiv.org/abs/2409.13456):
  - Ante-hoc explainable concept-bottleneck models: A class of hybrid models inserting interpretable intermediate outputs into the DNN architecture.
  - Post-hoc concept mining: Methods to find and explain prevalent latent space features of
DNNs which can help to find out biases.
  - Post-hoc concept extraction: Localize user-provided natural language concepts within the DNN latent space.
+ Mechanistic Interpretability: Probing, sparse autoencoders, causal abstractions.

This knowledge is deepened by a practical exercise part that aims to transfer the provided guidelines to real-world problems.

## Organizational
The tutorial will take place as part of the [European Conference on Artificial Intelligence 2025 (ECAI2025)](https://ecai2025.eu), Oct 25—30, 2025, Bologna, Italy.

- **When:** *exact date tba* (within Oct 25—30, 2025) <!-- TODO-->
- **Where:** Bologna, Italy. Check out the [ECAI2025 venues](https://ecai2025.org/venues/).
- **Format:** half-day tutorial at ECAI2025 both with lecture and practical parts.
- **Target audience**: We target both **researchers and practitioners** seeking to integrate explainability into their work.
- **Prerequisites:** Some basic knowledge about deep learning will be required; experience with pytorch will be helpful for the practical part, but not required.  
  **Both novices and experts** are welcome to join.
- **What to bring:** Feel free to bring and share your  explainability problem during the discussion part.

