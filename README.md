# SAMOT: State-Aware Step Modulation and Optimal Transport Matching for Audio-Visual Instance Segmentation

![ACM MM 2026](https://img.shields.io/badge/Conference-ACM%20MM%202026-00629B.svg)
![Code](https://img.shields.io/badge/Code-Coming%20Soon-orange.svg)

> **Status:** The official implementation is being prepared and will be released here.

## 📢 News

- **[2026-07-13]** SAMOT has been accepted by **ACM Multimedia 2026**! 🎉
- **[Coming Soon]** Training code, inference scripts, pre-trained models, and detailed documentation will be released here.

## 📖 Abstract

Audio-Visual Instance Segmentation (AVIS) aims to simultaneously classify, segment, and track sounding objects within video sequences. Unlike Audio-Visual Semantic Segmentation (AVS), AVIS involves instance-level modeling across longer video sequences, introducing two key challenges: (1) complex modality-state changes disrupt long-range modeling, and (2) substantial structural and distributional discrepancies between modalities hinder precise instance-level association. Existing methods rely on fixed-step Transformers and recursive Mamba models, lacking adaptability to modality-state changes. In addition, methods performing implicit matching ignore the inherent distributional inconsistencies. To address these issues, we propose **SAMOT**, a framework with **Adaptive Dynamic Step Modulation (ADSM)** and **Optimal Transport-based Matching Modulation (OT-MM)**. ADSM adapts Mamba step sizes from temporal variation, cross-modal discrepancy, and historical context, while OT-MM explicitly establishes instance-level cross-modal correspondence through entropy-regularized optimal transport and an MMD regularizer. SAMOT achieves state-of-the-art performance on benchmark AVIS datasets.

## 🏗️ Framework

The framework visualization will be released with the camera-ready materials and code.

## 🛠️ Usage

We are organizing the codebase and documentation.

- [ ] Release inference code
- [ ] Release training scripts
- [ ] Release pre-trained models
- [ ] Release dataset preparation instructions

**The full implementation will be available soon.**

## ✏️ Citation

Citation details will be added after the camera-ready version is finalized.
