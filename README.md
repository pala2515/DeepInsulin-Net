# DeepInsulin-Net
Deep Learning Model for A Deep Learning Model for Identifying Drug Interactions Leading to Specific Insulin-Related Adverse Events

<img width="524" height="749" alt="deepinsilun net" src="https://github.com/user-attachments/assets/e0653084-6827-4c4a-b18c-d9cd1a8c5a4f" />


🧠 DeepInsulin-Net: A Deep Learning Model for Identifying Drug Interactions Leading to Specific Insulin-Related Adverse Events

Author: Muhammed Ali Pala
Published in: Scientific and Academic Computing and Information Systems (SAUCIS)
Year: 2025, Volume: 8, Issue: 2, pp. 245–259
DOI: 10.35377/saucis...1646658

📘 Overview

DeepInsulin-Net is a deep learning-based framework designed to identify and predict insulin-related adverse drug-drug interactions (DDIs) with high accuracy and robustness.
The model addresses one of the most critical challenges in pharmacovigilance and clinical decision support systems — anticipating harmful reactions that may occur when insulin interacts with other medications.

⚙️ Methodology

Input Features:
Drug molecule properties are encoded using MACCS keys, Morgan fingerprints, and RDKit molecular descriptors.

Feature Optimization:
Low-variance features are removed using the variance thresholding technique to enhance classification performance.

Model Architecture:
A 1D Convolutional Neural Network (CNN) processes drug pairs in parallel input streams, effectively learning interaction patterns.

Imbalanced Data Handling:
A class-weighting strategy is employed to balance underrepresented side effect classes.

📊 Experimental Results

Training Accuracy: 99.66%

Validation Accuracy: 94.03%

Training Loss: 0.01

Validation Loss: 0.22

ROC-AUC: > 0.99

These results demonstrate that DeepInsulin-Net effectively predicts even rare adverse events, ensuring reliable and generalizable performance across insulin-related interactions.

🚀 Key Contributions

Introduces a novel deep learning framework for insulin-specific DDI prediction.

Provides a scalable and computationally efficient model suitable for large pharmacological datasets.

Enhances drug safety analysis by integrating cheminformatics and deep learning.


🧬 Citation

If you use this repository, please cite the following publication:


M. A. Pala, “DeepInsulin-Net: A Deep Learning Model for Identifying Drug Interactions Leading to Specific Insulin-Related Adverse Events”, SAUCIS, vol. 8, no. 2, pp. 245–259, 2025
doi: 10.35377/saucis...1646658.


