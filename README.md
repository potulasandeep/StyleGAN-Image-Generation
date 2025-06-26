# Code File:
https://colab.research.google.com/drive/1ooZVJpVorZJ2sOm0bZwxnu2KlRKizK_N?usp=sharing

# StyleGAN-Image-Generation

A PyTorch implementation of StyleGAN with progressive growing for high-quality image generation. This project defines custom layers (style mapping, adaptive instance normalization, noise injection), builds a generator and discriminator, and provides a training pipeline to progressively increase resolution.

# 📌 Project Overview

**Objective:** Implement StyleGAN architecture from scratch to generate realistic images through style-based synthesis and progressive resolution scaling.

**Key Components:**

**Style Mapping Network:** Transforms latent vectors into style embeddings.

**Adaptive Instance Normalization:** Injects style into feature maps.

**Noise Injection:** Adds stochastic variation at each block.

**Progressive Growing:** Starts training at low resolution and incrementally scales up to higher resolutions.

# 📊 Results & Sample Outputs

Generated images gradually improve in fidelity as training moves from 4×4 up to 128×128 resolution.
