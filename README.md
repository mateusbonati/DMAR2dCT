# DMAR2dCT: Deep Learning Metal Artifact Reduction for 2D Computed Tomography

## Overview

"DMAR2dCT" stands for Deep Learning Metal Artifact Reduction for 2D Computed Tomography. This project is the culmination of a Final Paper developed during my graduation in Electrical Engineering at the University of São Paulo (USP). The core of this project is a neural network designed to reduce artifacts caused by metallic objects in computed tomography (CT) images.

## Objective

The primary objective of this work is to develop and evaluate a method to reduce metal artifacts in CT images using convolutional neural networks (CNNs), applied directly to the sinogram. This approach aims to enhance the quality of CT scans, particularly in the presence of metal implants, to facilitate more accurate medical diagnoses.

## Methodology

### The Problem of Metal Artifacts in CT Scans

- Metal artifacts in CT images appear as luminous bands resulting from the interaction of X-ray photons with metallic objects, degrading the image quality.
- These artifacts can significantly impair medical diagnosis by obscuring or altering the appearance of the scanned tissues.

### Approach

- Our method uses advanced machine learning techniques, specifically CNNs, to process the sinogram directly.
- The processing of the sinogram, rather than the reconstructed image, allows for a more effective reduction of artifacts.

### Evaluation and Results

- The method was evaluated using the Shepp-Logan phantom.
  
  ![Shepp-Logan phantom.](https://github.com/mateusbonati/DMAR2dCT/blob/main/shepp%20logan.png)

- We compared our results with traditional artifact reduction methods like interpolations.
- The evaluation metrics included mean squared error, peak signal-to-noise ratio, and structural similarity index.

## Results

- The proposed method outperformed other evaluated approaches in reducing artifacts.

   ![Projections for θ = 90 degrees of the corrected sinogram using methods compared to the sinogram without metal.
  ](https://github.com/mateusbonati/DMAR2dCT/blob/main/grafico1.png)
  
- The results indicate a significant improvement in image quality, making it a viable alternative for clinical applications.
  
  ![Results:](https://github.com/mateusbonati/DMAR2dCT/blob/main/result.png)
  



### Code Availability

The code for "DMAR2dCT" is also available on the GitHub repository of the Computer Vision Laboratory at USP. You can access it here: [DMAR2dCT GitHub Repository](https://github.com/LAVI-USP/DMAR2dCT)




