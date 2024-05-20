
# Real-time Image Enhancement using Adaptive Histogram Equalization and Deep Learning Techniques


## Table of Contents

- [Abstract](#abstract)
- [Introduction](#introduction)
- [Literature Review](#literature-review)
- [Proposed Methodology](#proposed-methodology)
- [Results and Visualization](#results-and-visualization)
- [Conclusion](#conclusion)
- [References](#references)
- [Authors](#authors)
- [License](#license)

## Abstract

In this project, we propose a novel approach that integrates the adaptive histogram equalization algorithm with deep learning models for image enhancement. The adaptive histogram equalization technique is widely used in image processing to improve the contrast and dynamic range of images. However, it often leads to over-enhancement and amplification of noise artifacts. To address these limitations, we introduce deep learning models that can learn and adaptively enhance the image while preserving its natural appearance and reducing noise.


## Introduction

In recent years, the demand for real-time image enhancement has grown exponentially, driven by the increasing need for visually appealing and high-quality images in various applications. To address this challenge, researchers have been exploring the synergistic combination of adaptive histogram equalization (AHE) and deep learning techniques. This approach aims to enhance the visual quality and appearance of images in real-time by leveraging the power of AHE to redistribute pixel intensities and the capabilities of deep learning models to learn complex image representations.

### Importance of Contrast Enhancement in Image Processing

- **Better Visualization**: Enhances the visual appearance, making it easier for human observers to interpret and understand content.
- **Feature Extraction**: Improves the extraction of features and patterns from images.
- **Image Restoration**: Reveals hidden details in low-contrast images.
- **Medical Imaging**: Crucial for accurate diagnosis by enhancing subtle structures and anomalies.
- **Surveillance and Security**: Improves visibility in low-light or challenging conditions.

## Literature Review

Several studies have investigated the combination of adaptive histogram equalization (AHE) and deep learning techniques for real-time image enhancement. For instance, Chen et al. (2017) demonstrated that CNNs can effectively learn the mapping between low-quality images and their enhanced versions, resulting in visually pleasing and natural-looking images.


## Proposed Methodology

### Contrast Enhancement Methods

1. **Histogram Equalization (HE)**
   - Redistributes pixel intensity values to achieve a uniform histogram distribution.

2. **Adaptive Histogram Equalization (AHE)**
   - Applies local histogram equalization to enhance local contrast.

3. **Contrast-Limited Adaptive Histogram Equalization (CLAHE)**
   - Limits contrast amplification to avoid over-enhancement.

4. **Local Region Stretch (LRS)**
   - Enhances contrast based on brightness variations, suitable for uneven illumination.

### Deep Learning Model

- **Convolutional Neural Network (CNN)**
  - Designed and trained using a large dataset of images with ground truth labels for enhanced visual quality.

### Evaluation Metrics

- **Quantitative**: PSNR, SSIM, MSE
- **Qualitative**: Visual comparison and subjective assessment

![CNN Architecture](Image-Processing/car.jpg)

## Results and Visualization

### Histogram Equalization (HE)

![HE Result](path/to/he_result/image.jpg)

**Conclusion**: Effectively enhances contrast but may amplify noise.

### Adaptive Histogram Equalization (AHE)

![AHE Result](path/to/ahe_result/image.jpg)

**Conclusion**: Enhances local contrast effectively but may over-amplify noise.

### Contrast-Limited Adaptive Histogram Equalization (CLAHE)

![CLAHE Result](path/to/clahe_result/image.jpg)

**Conclusion**: Balances contrast enhancement and noise amplification, resulting in visually pleasing images.

### Local Region Stretch (LRS)

![LRS Result](path/to/lrs_result/image.jpg)

**Conclusion**: Effectively enhances contrast by considering brightness levels individually.

## Conclusion

This project presents a real-time image enhancement system that combines adaptive histogram equalization and deep learning techniques. The proposed method enhances the visual quality of images by improving contrast, brightness, and overall appearance while reducing noise artifacts. The results validate the effectiveness of the proposed approach and highlight its potential applications in various fields such as medical imaging, surveillance, and entertainment.

## Authors

- **Sanat Prasad**
- **Prakshaal Jain**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

