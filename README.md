# Diffusion Facial Forgery Detection

This repository contains the DiFF dataset proposed in our paper, [Diffusion Facial Forgery Detection](https://arxiv.org/abs/2401.15859)

[PDF](https://arxiv.org/abs/2401.15859)

## Abstract

Detecting diffusion-generated images has recently grown into an emerging research area. Existing diffusion-based datasets predominantly focus on general image generation. However, facial forgeries, which pose a more severe social risk, have remained less explored thus far. To address this gap, this paper introduces DiFF, a comprehensive dataset dedicated to face-focused diffusion-generated images. DiFF comprises over 500,000 images that are synthesized using thirteen distinct generation methods under four conditions. In particular, this dataset leverages 30,000 carefully collected textual and visual prompts, ensuring the synthesis of images with both high fidelity and semantic consistency. We conduct extensive experiments on the DiFF dataset via a human test and several representative forgery detection methods. The results demonstrate that the binary detection accuracy of both human observers and automated detectors often falls below 30%, shedding light on the challenges in detecting diffusion-generated facial forgeries. Furthermore, we propose an edge graph regularization approach to effectively enhance the generalization capability of existing detectors.

## Dataset Download

For synthesised images,

Google Drive: [Link](https://drive.google.com/drive/folders/13uTBF7-YkqtpGNjc9QvqzaBfBJ5fe7-w?usp=drive_link)

We are currently reviewing the corresponding pristine images and prompts, and will conditionally release them in the near future.

## Citation

If you find this work helps, please cite our paper:

```
@misc{cheng2024diffusion,
      title={Diffusion Facial Forgery Detection}, 
      author={Harry Cheng and Yangyang Guo and Tianyi Wang and Liqiang Nie and Mohan Kankanhalli},
      year={2024},
      eprint={2401.15859},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```


