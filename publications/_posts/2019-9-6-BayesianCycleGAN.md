---
layout: publication
title: Bayesian CycleGAN
manuscript: True
authors: <b>Haoran You</b>, Yu Cheng, Chunliang Li, Tianheng Cheng, Pan Zhou
reviewing: False
available: True
booktitle: CVPR
year: 2019
---
Recent techniques built on Generative Adversarial Networks (GANs) like CycleGAN are able to learn mappings between domains from unpaired datasets through min-max optimization games between generators and discriminators. However, it remains challenging to stabilize the training process and diversify generated results.
To address these problems, we present the nontrivial Bayesian extension of cyclic model and an integrated cyclic framework for inter-domain mappings. The proposed method stimulated by Bayesian GAN explores the full posteriors of Bayesian cyclic model (with latent sampling) and optimizes the model with maximum a posteriori (MAP) estimation. Hence we name it Bayesian CycleGAN. We perform the proposed Bayesian CycleGAN on multiple benchmark datasets, including Cityscapes, Maps, and Monet2photo. The
quantitative and qualitative evaluations demonstrate the proposed method can achieve more stable training, better
performance and diversified images generating.