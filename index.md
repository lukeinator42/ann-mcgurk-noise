---
layout: default
title: The Importance of Noise in Audiovisual Learning
---

# The Importance of Noise in Audiovisual Learning: An Artificial Neural Network Simulation of the McGurk Effect

**Authors:** Lukas Grasse, Matthew Tata  
**Affiliation:** Canadian Centre for Behavioural Neuroscience, University of Lethbridge

## Introduction

This study explores the McGurk effect, an auditory-visual illusion where incongruent inputs lead to a fused, but incorrect, auditory percept. We investigate how the presence of noise influences the fusion of auditory and visual cues during this effect.

## Methodology

- **Dataset:** Audiovisual dataset of nine word pairs.
- **Participants:** Tested on humans and artificial neural networks (ANNs) trained on audiovisual speech.
- **ANN Models:** Deep AVSR, AV-HuBERT, and our AudioVisual CPC network with varying noise levels during training.

## Results

Our findings suggest that training on audiovisual speech with noisy audio is important for replicating the illusion. The biologically plausible self-supervised training most closely approached human performance on the McGurk effect.

![McGurk Stimuli Classification Results](/assets/stacked_dataset_percentages_audiovisual_condition_grouped_by_noise.pdf)

_Figure 1: McGurk Stimuli Classification Results_

## Discussion

ANNs exhibit the McGurk effect under certain circumstances, with a gap between ANN and human behavior even as ANNs approach human-level ability on audiovisual speech recognition tasks.

## References

1. Afouras, T., Chung, J. S., Senior, A., Vinyals, O., & Zisserman, A. (2018). Deep audio-visual speech recognition. IEEE Transactions on Pattern Analysis and Machine Intelligence.
2. Dekle, D. J., Fowler, C. A., & Funnell, M. G. (1992). Audiovisual integration in perception of real words. Perception & Psychophysics.
3. Kanwisher, N., Khosla, M., & Dobs, K. (2023). Using artificial neural networks to ask 'why' questions of minds and brains. Trends in Neurosciences.
4. Shi, B., Hsu, W.-N., & Mohamed, A. (2022). Robust self-supervised audio-visual speech recognition. arXiv preprint arXiv:2201.01763.

[GitHub Repository](https://github.com)

For inquiries, contact [lukas.grasse@uleth.ca](mailto:lukas.grasse@uleth.ca).
