# Credit Card Fraud Detection: Tackling Class Imbalance in Machine Learning

In this project, I tackled the challenge of detecting fraudulent credit card transactions in a highly imbalanced dataset, where fraudulent cases represent just 0.17% of the total. This extreme imbalance made traditional accuracy-based metrics misleading and highlighted the need for smarter evaluation strategies.

# 🧪 Approach
I built and evaluated two models — Logistic Regression and Decision Trees — across three data configurations:

* Original (Imbalanced): Real-world distribution with minimal fraud exposure

* Oversampled: Increased representation of fraud cases by duplicating minority samples

* Undersampled: Reduced legitimate transactions to balance the dataset

# 📊 Key Findings
* Models trained on the original dataset achieved high accuracy but failed to detect most fraud cases.

* Oversampling significantly improved recall (sensitivity), helping the models catch more fraudulent activity while maintaining acceptable precision.

* Undersampling also improved recall but led to reduced generalization due to loss of valuable non-fraud data.

# 🔑 Best Performer: Logistic Regression on the Oversampled Dataset
This model struck the best balance between recall and precision, making it the most reliable option for fraud detection.

# 💡 Takeaways
* Accuracy isn't enough: In imbalanced settings, recall, precision, and F1-score are far more informative.

* Sampling strategy matters: How you prepare your data can be just as important as the model you choose.

* Domain context drives modeling decisions: Metrics and evaluation should align with the real-world costs of false negatives.

# 🚀 Future Work
To build on this work, I plan to:

* Explore ensemble methods (e.g., Random Forests, XGBoost)

* Experiment with SMOTE for synthetic oversampling

* Fine-tune classification thresholds for better fraud detection balance
