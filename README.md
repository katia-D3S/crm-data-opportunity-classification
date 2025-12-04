# crm-data-opportunity-classification
Classifying CRM opportunities into data vs. non-data projects using supervised learning.

A company provides expert services in data science, AI, pricing, supply chain, HR analytics, and technology implementation. Sales representatives log all business opportunities in a CRM system and are responsible for tagging opportunities that involve data-related work (e.g., data platforms, predictive algorithms, analytics tools).
However, the company discovered that these “data” tags are often applied inconsistently. Many opportunities that should have been labeled as data-related were incorrectly marked as “non-data,” leading to an underestimation of the true data-project pipeline.
To address this, the goal of the project is to develop an automated method to classify business opportunities as “data” or “non-data” based on CRM information.
A historical dataset of over 3,000 opportunities is provided, though some entries may be mislabeled by the sales team. All opportunities tagged as “data” are considered correctly labeled, but some “non-data” entries may actually belong to the data category.
This study evaluates the feasibility of building such an automated classification system by applying multiple machine-learning models and comparing their performance.

📌 The following supervised learning algorithms were implemented and compared (precision, recall, F1-score, and accuracy):
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier
- Support Vector Machine (SVM)
