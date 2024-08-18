# Lung Segmentation Using Chexpert Dataset
### Made in December 2023

## Project Overview
This project focuses on lung segmentation in medical imaging using the Chexpert dataset. Lung segmentation is a crucial step in diagnosing various pulmonary diseases, and accurate segmentation can significantly improve diagnostic outcomes. This repository includes the implementation of two different models—CycleGAN and Segment Anything Model (SAM)—to achieve effective lung segmentation.

## Dataset
### Chexpert Dataset
- **Description:** The Chexpert dataset is a large dataset of chest X-rays, used widely for medical imaging research.
- **Characteristics:** The dataset contains a vast number of labeled chest X-ray images, making it highly relevant for tasks like lung segmentation.
- **Relevance:** The dataset is particularly useful for training deep learning models aimed at identifying and segmenting lung areas in X-ray images.
## Approaches
### 1. CycleGAN
- **Model Explanation:** CycleGAN is a type of Generative Adversarial Network (GAN) that can translate images from one domain to another without paired examples.
- **Application:** In this project, CycleGAN is applied to generate lung segmentation masks from chest X-ray images.
- **Advantages:** CycleGAN's ability to work with unpaired data makes it suitable for tasks where exact ground truth masks are difficult to obtain.
### 2. SAM (Segment Anything Model)
- **Model Introduction:** SAM is a model designed to generalize well to a variety of segmentation tasks, including medical imaging.
- **Application:** SAM is utilized in this project to segment lung regions from the Chexpert dataset.
- **Benefits:** SAM's versatility and generalization capabilities make it a strong candidate for medical image segmentation tasks.
## Project Methodology
- **Comparative Analysis:** A comparative analysis of CycleGAN and SAM was conducted to evaluate their effectiveness in lung segmentation.
- **Testing and Validation:** The models were tested and validated on a subset of the Chexpert dataset, with a focus on accuracy and segmentation quality.
- **Evaluation Criteria:** Segmentation accuracy was evaluated using standard metrics to determine the performance of each approach.
## Conclusion and Future Directions
- **Summary of Findings:** The project successfully implemented and evaluated two approaches for lung segmentation, providing insights into their respective strengths and weaknesses.
- **Implications:** These findings have significant implications for improving diagnostic tools in medical imaging.
- **Future Research:** Future work may involve exploring other deep learning models or enhancing the current models to further improve segmentation accuracy.
