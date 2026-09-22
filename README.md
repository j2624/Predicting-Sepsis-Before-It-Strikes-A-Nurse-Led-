# Predicting-Sepsis-Before-It-Strikes-A-Nurse-Led-


Background: Sepsis remains a leading cause of preventable mortality in intensive care units, and early detection significantly improves patient outcomes. Existing early-warning systems often rely on simple scoring rules that may miss complex, evolving physiological patterns.

Aim: To describe a self-directed project in which a registered nurse developed a hybrid deep learning model combining LSTM and Transformer-style attention mechanisms to predict sepsis onset from ICU time-series data.

Method: A hybrid LSTM–Transformer model was built and trained on the publicly available PhysioNet/Computing in Cardiology Challenge 2019 dataset (40,336 de-identified ICU patient records), using 48-hour sequences of vital signs, laboratory values, and fixed patient factors. Class imbalance was addressed using weighted loss, and regularisation techniques (dropout, L2) were applied to reduce overfitting. No NHS patient data was used.

Results: The final model achieved 90% overall accuracy, with a recall of 66% and precision of 27% for sepsis cases at a clinically-informed decision threshold, correctly identifying the majority of sepsis cases while balancing alert burden. Model performance and architecture choices are illustrated through confusion matrices, autocorrelation analysis, and layer-wise visualisations.

Conclusion: This project demonstrates that a frontline nurse can independently design, build, and evaluate an advanced deep learning model for a clinically significant problem, applying self-directed CPD in data science and AI to real-world patient safety challenges.
