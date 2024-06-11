# CancerNet: A machine learning approach to predict and classify Cancer.<br>
---
## Introduction:<br>

The early and accurate detection of cancer is crucial for effective treatment and improving patient outcomes. However, manually analyzing medical imaging data for cancer diagnosis is a time-consuming and error-prone process, often leading to delays in treatment or missed diagnoses. To address this challenge, we developed CancerNet, a cutting-edge deep learning solution that leverages the power of advanced neural networks and machine learning techniques to automate the process of cancer detection and classification from medical imaging data.

CancerNet is built upon a robust and diverse dataset comprising over 100,000 images spanning 8 main cancer classes and 26 sub-classes, providing a comprehensive foundation for training and evaluating the models. By employing transfer learning techniques and fine-tuning pre-trained deep neural networks on this specialized dataset, CancerNet harnesses the learned features from large-scale image recognition tasks and adapts them to the cancer classification domain, enabling accurate and efficient cancer detection and classification.
<br>

## Approach used for the project:<br>

> ### A.Dataset used: <br>
>>  - Dataset contains over 100,000 images of cellular images of 8 main classes of cancer and 26 sub-classes of cancer,<br>
>>  - each subclass contains about 5000 images. <br>
<br>

> ### B.Model Training: <br>
>>  - Applied Transfer Learning and trained different models with different architectures and hyperparameters, then ensembled their predicitions to boost overall accuracy and robustness of predictions.
>>  - Implemented Gradient Accumulation to overcome low GPU memory limitations, enabling training of larger models and processing large batches of data.

> ### C.User Interface:<br>
>>  - Created a simple UI with the help of Gradio.<br>
>>  - Users can input an cellular image, and the models return the type of cancer detected in the image.<br>
---

## Future of this project:<br>
- To create a larger ensemble of various large pretrained models to get a greater boost and further increment robustness of the predictions.<br>
- Add various augmentation strategies to further increase the accuracy.<br>
- Host the application and make it accessible for users.
---



