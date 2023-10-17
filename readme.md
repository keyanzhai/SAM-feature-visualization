# SAM Feature Visualization

## Single Point as the prompt

Refer to this [notebook](https://github.com/keyanzhai/SAM-feature-visualization/blob/main/single-point-prompt/single-prompt-features.ipynb).

## A grid of points as the prompt

Refer to this [notebook](https://github.com/keyanzhai/SAM-feature-visualization/blob/main/grid-points-prompt/grid-prompt-features.ipynb).

## Example

E.g. A synthetic hand + cup image with the prompt point at the hand's thumb.

### Original image
![Original Image](single-point-prompt/output/vit-h/view1/0-original-image.png)

### Initial Image Embedding (256-d reduced with PCA)

![Image Embedding](single-point-prompt/output/vit-h/view1/1-initial-image-embedding-gray.png)

![Alt text](single-point-prompt/output/vit-h/view1/1-initial-image-embedding.png)

![Alt text](single-point-prompt/output/vit-h/view1/1-initial-image-embedding-pca.png)

### Image Embedding after the first decoder block

![Alt text](single-point-prompt/output/vit-h/view1/2-4-decoder1-step4-image-embedding-gray.png)

![Alt text](single-point-prompt/output/vit-h/view1/4-updated-image-embedding.png)

![Alt text](single-point-prompt/output/vit-h/view1/4-updated-image-embedding-pca.png)

### Image Embedding after the second decoder block

![Alt text](single-point-prompt/output/vit-h/view1/4-updated-image-embedding-gray.png)

![Alt text](single-point-prompt/output/vit-h/view1/4-updated-image-embedding.png)

![Alt text](single-point-prompt/output/vit-h/view1/4-updated-image-embedding-pca.png)

### Upscaled Image Embedding

![Alt text](single-point-prompt/output/vit-h/view1/5-upscaled-image-embedding-gray.png)

![Alt text](single-point-prompt/output/vit-h/view1/5-upscaled-image-embedding.png)

![Alt text](single-point-prompt/output/vit-h/view1/5-upscaled-image-embedding-pca.png)

### Low Resolution Masks

![Alt text](single-point-prompt/output/vit-h/view1/6-low-res-masks.png)

### Original Resolution Masks

![Alt text](single-point-prompt/output/vit-h/view1/7-original-res-masks.png)

### Binarized Masks

![Alt text](single-point-prompt/output/vit-h/view1/8-binarized-masks.png)

### Masked RGBA Images

![Alt text](single-point-prompt/output/vit-h/view1/final/view1_part_1.png)
![Alt text](single-point-prompt/output/vit-h/view1/final/view1_part_2.png)
![Alt text](single-point-prompt/output/vit-h/view1/final/view1_part_3.png)