# Identifying Human and Bot Accounts on Twitter Using Machine Learning | Fall 2024
Twitter Bot Account Classification | Fall 2024
This is the repository for the Twitter Bot Account Classification project done in Applied Machine Learning course during Fall 2024. The project focuses on identifying human-operated and bot-operated Twitter accounts using machine learning techniques. The goal is to address the rising concerns over misinformation and malicious content dissemination by leveraging data science to classify accounts accurately. The project utilizes a Kaggle dataset containing information on 37,438 Twitter accounts described by 19 features, including metadata (e.g., account age, followers count), behavioral insights (e.g., tweets per day), and descriptive attributes (e.g., profile description, verified status). The primary tasks of the project include:

- Data preprocessing and analysis: Preparing and cleaning data to ensure high-quality input for model training. Exploratory data analysis includes: 1). Log transformation and normalization for highly skewed features; 2). Feature engineering, including creating new boolean features and addressing multicollinearity and removing redundant features.
- Model experimentation and optimization: Implementing and tuning a range of machine learning models using stratified sampling to maintain class balance. Hyperparameter optimized for models to improve classification accuracy.
- Model performance evaluation: Using metrics such as AUC, precision, recall, and F1-score to identify the most effective approach, XGBoost  with an AUC of 0.9341 and F1-score of 0.8056, for classification.

Please feel free to email me at ruoheng.du@columbia.edu for any more information.

* This project is done in collaboration with Shivank Agrawal, Yiwen Ge, and Yandong Xiang.

<img width="600" alt="technique" src="https://github.com/ruoheng-du/human-bot-account/raw/main/assets/technique.png">
<img width="600" alt="results" src="https://github.com/ruoheng-du/human-bot-account/raw/main/assets/results.png">