# Master's Thesis Report LaTeX Document
## The University of Texas at Austin, Oden Institute for Computational Science and Engineering

This repository contains the LaTeX code to generate the official PDF document for
"Investigation of Transformer-based Methods for Image Compression, Analysis, and Generation"

Report
=============================================================
The report includes a summary of my research, experimentation,
and development using vision transformers (ViT).
Transformer-based vision models (i.e. sequential, generalizable, overparameterized "language" models adapted for computer vision using the attention mechanism) are still very nascent.
The original contribution of this project lies in exploring a novel approach for quantifying image quality from neural image compression and generation using a generative adversarial network (GAN) architecture.

### Contents

#### 1. Introduction to Vision Transformers
##### 1.1. Motivation (generalization, overparameterization)
##### 1.2. Brief History (language models, emphasize, linearity)
##### 1.3. Principles of Operation (diagrams) 
##### 1.4. Formulation (math)
##### 1.5. Implementations (pre-trained models, ViT)
##### 1.6 Computational constraints (training)

#### 2. Literature Review: Vision Transformers, Neural Image Compression, JPEG(related work)
##### 2.1. Image is worth 16x16 and the ViT
##### 2.2. Transformer-based Image Compression (Ming Lu) and Towards End-to-End Image Compression and Analysis with Transformers (Yuanchao Bai)(hasn't been achieved yet)
##### 2.4. TransGANs (low quality, CIFAR-10 32x32)
##### 2.5. Principles of JPEG compression (de facto benchmark)
###### 2.5.1 Deterministic
##### 2.6. Neural compression (novelty and coveted future)
###### 2.6.1 Probabilistic
##### 2.7. Metrics: SSIM, MSE, PSNR, BRISQUE

#### 3. Neural Image Compression and Generation (Theory and Practice)
##### 3.1. Generative image compression overview (vineeth)
###### 3.1.1 Architecture
###### 3.1.2 Latent space vector representation after compression
##### 3.2. Outputs from implementation, graphs, tables
##### 3.3. Visual Inspection (natural performance asymptote)
##### 3.4. GAN Quantitative (FID score, inception score)
##### 3.5. Difference vs original, SSIM, MSE, PSNR, BRISQUE (and definitions of each)
##### 3.6. Optimization Techniques (reducing learning_rate as the model trains)
##### 3.7. ViT before, ViT after (Transformer Score)

#### 4. Discussion
##### 4.1. Results
##### 4.2. Approaches to improve
##### 4.3. Future of Vision Transformers, Compression, and Generation
##### 4.4. Coveted Deep learning based Image compression 
##### 4.5. Training (like GPT-3 trained on all internet text, Vision T trained on all google images)
##### 4.6. Cost ($100M+), GPT-3 cost $10M-$20M

#### 5. Summary
##### 5.1. Key contributions (experimentation with Vision Transformers, nascent field)
##### 5.2. Takeaways
##### 5.3. Acknowledgments (LIVE lab, TACC)
##### 5.4. Closing Remarks

#### Bibliography

#### Appendix
##### A. Technologies used:
###### A.1 GPU, Local machine
###### A.2 TACC, Stampede2, job submission process
###### A.3 PyTorch implementations