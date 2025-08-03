# IBM_Cloud_project
Power System Fault Detection and Classification

problem statement:
Design a machine learning model to detect and classify different types of faults in a power distribution system. Using electrical measurement data (e.g., voltage and current 
phasors), the model should be able to distinguish between normal operating conditions and various fault conditions (such as line-to-ground, line-to-line, or three-phase faults). The objective is to enable rapid and accurate fault identification, which is crucial for maintaining power grid stability and reliability.

solution:
The proposed system aims to address the challenge of accurately detecting and classifying power system faults to ensure a stable and reliable electricity distribution network. This involves leveraging machine learning techniques to analyze electrical parameters and distinguish between normal and faulty conditions. The solution will consist of the following components:
Data Collection:
 Use the Kaggle dataset containing voltage and current phasors under normal and fault conditions (line-to-ground, line-to-line, three-phase).
Data Preprocessing:
 Clean the data, handle missing values and outliers, normalize features, and extract relevant parameters for accurate classification.
Machine Learning Algorithm:
 Train and compare supervised models (e.g., Random Forest, SVM, Neural Networks) to classify faults. Select the best-performing model based on accuracy and robustness.
Deployment:
 Build a real-time application deployed on IBM Cloud Lite using Watson Studio, Cloud Functions, and Cloud Object Storage.
Evaluation:
 Measure performance using accuracy, precision, recall, and F1-score. Apply cross-validation and monitor model performance for future updates.

<img width="1918" height="813" alt="Screenshot 2025-08-03 155436" src="https://github.com/user-attachments/assets/1b3ce597-2f00-4120-aac2-7add93a64d40" />

<img width="1890" height="769" alt="Screenshot 2025-08-03 155503" src="https://github.com/user-attachments/assets/0c30061c-faae-4b34-87ef-343d4e4d0aa4" />

<img width="1893" height="563" alt="Screenshot 2025-08-03 170215" src="https://github.com/user-attachments/assets/8ae23f32-c7c6-4c3c-a595-0836fd669e0f" />

<img width="1815" height="659" alt="Screenshot 2025-08-03 170135" src="https://github.com/user-attachments/assets/b8825fc8-6c51-49ac-a654-a70aead66326" />

