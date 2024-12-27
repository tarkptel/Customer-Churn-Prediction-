</head>
<body>
    <header>
        <h1>Customer Churn Prediction Project</h1>
    </header>
    <main>
        <section>
            <h2>Introduction</h2>
            <p>This project aims to predict customer churn in the telecom industry using machine learning models. Churn refers to customers discontinuing their service with the company. The goal is to identify potential churners and take proactive measures to retain them.</p>
        </section>

  <section>
            <h2>Data Overview</h2>
            <p>The dataset includes customer demographics, account information, service usage, and target churn labels. The target variable is 'Churn Label' which indicates whether a customer has churned or not.</p>
        </section>
   <section>
            <h2>Exploratory Data Analysis (EDA)</h2>
            <p>During EDA, the following key insights were discovered:</p>
            <ul>
                <li>Customers with higher monthly charges are more likely to churn.</li>
                <li>Long-tenured customers tend to have lower churn rates.</li>
                <li>Churn rates vary significantly across different contract types, with month-to-month contracts having the highest churn rate.</li>
            </ul>
        </section>
    <section>
            <h2>Data Preprocessing</h2>
            <p>Steps taken to clean and preprocess the data:</p>
            <ul>
                <li>Handled missing or empty values in 'Total Charges' column by replacing empty strings with mean values.</li>
                <li>Converted the 'Total Charges' column to <code>float64</code>.</li>
                <li>Applied techniques to handle class imbalance, such as SMOTE.</li>
            </ul>
        </section>

   <section>
           <h2>Feature Engineering</h2>
            <p>Key features created to improve the model:</p>
            <ul>
                <li>Tenure Buckets</li>
                <li>Monthly Charges</li>
                <li>Total Charges derived features</li>
            </ul>
        </section>

  <section>
            <h2>Algorithms Used</h2>
            <p>Several algorithms were considered for this project. The following are the key ones:</p>
            <ul>
                <li>Logistic Regression</li>
                <li>Random Forest Classifier</li>
                <li>Gradient Boosting Algorithms (e.g., XGBoost, LightGBM)</li>
                <li>XGBoost Classifier</li>
            </ul>
        </section>

   <section>
            <h2>Why Random Forest?</h2>
            <p>Random Forest was chosen as the primary model because of its ability to handle complex datasets with high accuracy and robustness. In this project, it achieved a high F1-Score of 0.870142, which reflects a balanced trade-off between Precision and Recall. Additionally, Random Forest is less prone to overfitting compared to other algorithms and performs well even with limited feature engineering.</p>
        </section>

  <section>
            <h2>Model Evaluation</h2>
            <p>Random Forest Classifier was implemented and evaluated using the following metrics:</p>
            <ul>
                <li><b>Precision:</b> 0.857</li>
                <li><b>Recall:</b> 0.808</li>
                <li><b>F1-Score:</b> 0.832</li>
                <li><b>Accuracy-Score:</b> 0.823</li>
            </ul>
            <p>The equal values of Precision, Recall, and F1-Score indicate a well-balanced model in terms of predicting True Positives and minimizing False Positives and False Negatives.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Customer Churn Prediction Project</p>
        <p>Author: Tark Patel</p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/tark-patel">@tark-patel</a></p>
    </footer>
</body>
</html>

