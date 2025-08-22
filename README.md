Underwater images often face challenges due to
 turbidity caused by suspended particles, leading to hazy and
 distorted visuals. The lack of real-life underwater data also
 reduces the efficiency of trained models. This code introduces
 a diffusion model-based denoising architecture to restore under
water turbid images. The method first quantifies the turbidity
 noise by optimizing the variance parameter using a dataset
 that replicates the diffusion process of forward noise addition.
 The trained U-Net architecture then iteratively reconstructs
 turbid images by implementing a reverse Markov diffusion chain
 process. In addition to visual enhancements, restored images are
 evaluated using perceptual evaluation measures such as entropy
 and the naturalness image quality evaluator. The results of this
 project will contribute significantly to underwater research by
 facilitating the monitoring of marine ecosystems and studying
 f
 ish migration patterns.
 Index Terms—Underwater Images, Image Restoration, Diffu
sion Models
