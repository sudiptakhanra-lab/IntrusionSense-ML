Network Intrusion Detection and Explainable Machine Learning
The growth of Internet of Things (IoT) networks has heightened the demand for advanced network intrusion detection systems (IDS). Traditional cybersecurity methods often fall short in these dynamic environments, making machine learning (ML) an essential approach for detecting malicious activities in IoT networks. ML-driven IDS provide effective and accurate identification of network attacks with high performance.

However, many ML models act as ‘black boxes,’ lacking transparency and interpretability, which can reduce user trust and hinder wider adoption. This project uses the UNSW-NB15 dataset, which contains labeled network traffic data distinguishing between normal and attack activities.

Three ML classifiers—Decision Trees, Multi-Layer Perceptrons, and XGBoost—were trained on this dataset. These models, alongside a network forensic system leveraging flow-based features, demonstrate strong performance in identifying botnet and other suspicious activities.

To enhance model interpretability, this work integrates Explainable AI (XAI) methods using Scikit-Learn, LIME, ELI5, and SHAP libraries. These tools provide visual insights into the decision-making processes of the classifiers, making the predictions more transparent and understandable to cybersecurity professionals.

The results confirm that combining traditional machine learning with XAI techniques is a practical approach to improving trust and usability in network security systems.

Dataset
The dataset used in this study is publicly available at Kaggle UNSW-NB15 Dataset.

Background
This project builds on prior work completed for an academic course focused on operations analytics at Ohio State University (Spring 2020). The earlier research involved binary classification using multilinear and logistic regression to predict behavioral and attack types in network traffic.
