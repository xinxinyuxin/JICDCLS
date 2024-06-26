# JICDCLS
JOINT END-TO-END IMAGE COMPRESSION AND DENOISING: LEVERAGING CONTRASTIVE LEARNING AND MULTI-SCALE SELF-ONNS


**Official PyTorch Implementation for [JOINT END-TO-END IMAGE COMPRESSION AND DENOISING: LEVERAGING CONTRASTIVE LEARNING AND MULTI-SCALE SELF-ONNS].**


> **JOINT END-TO-END IMAGE COMPRESSION AND DENOISING: LEVERAGING CONTRASTIVE LEARNING AND MULTI-SCALE SELF-ONNS** <br>
>  Yuxin Xie, Li Yu, Farhad Pakdaman, and Moncef Gabbouj <br>


## Introduction
Noisy images are a challenge to image compression algorithms due to the inherent difficulty of compressing noise. As noise cannot easily be discerned from image details, such as high-frequency signals, its presence leads to extra bits needed for compression. Since the emerging learned image compression paradigm enables end-to-end optimization of codecs, recent efforts were made to integrate denoising into the compression model, relying on clean image features to guide denoising. However, these methods exhibit suboptimal performance under high noise levels, lacking the capability to generalize across diverse noise types. In this paper, we propose a novel method integrating a multi-scale denoiser comprising of Self Organizing Operational Neural Networks, for joint image compression and denoising. We employ contrastive learning to boost the network ability to differentiate noise from high frequency signal components, by emphasizing the correlation between noisy and clean counterparts. Experimental results demonstrate the effectiveness of the proposed method both in ratedistortion performance, and codec speed, outperforming the current state-of-the-art.


## Installation
* NVIDIA-SMI 550.90.07
* CUDA Version: 12.4
* GPU: GeForce RTX 4090
* pip install -e .
* pip install pyyaml
* pip install opencv-python
* pip install tensorboard
* pip install imagesize
* pip install image_slicer
* pip install h5py
* pip install .

  






