🏡 California Housing Price Prediction

An end-to-end Machine Learning project that predicts housing prices using the California Housing Dataset.
This project demonstrates complete ML workflow including data preprocessing, stratified sampling, pipeline creation, model training, and evaluation.

📌 Project Overview
The goal of this project is to build a reliable regression model that predicts median house values based on various features such as income, location, housing age, and population.
This project focuses on:
* Data Cleaning & Preprocessing
* Stratified Sampling
* Feature Engineering
* Machine Learning Pipelines
* Model Comparison & Evaluation

📊 Dataset Information

The dataset contains information such as:
* Median Income
* Total Rooms
* Total Bedrooms
* Population
* Households
* Housing Median Age
* Ocean Proximity
* Median House Value (Target Variable)

Stratified Sampling was performed using income categories to ensure balanced train-test distribution.

⚙️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Scikit-Learn
* VS Code

🔄 Machine Learning Workflow

1️⃣ Data Preprocessing

* Handling missing values using `SimpleImputer`
* Encoding categorical variables using `OneHotEncoder`
* Feature scaling using `StandardScaler`

2️⃣ Stratified Sampling

Used `StratifiedShuffleSplit` based on income categories to maintain proper data distribution.

3️⃣ Model Training

Implemented and compared:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

4️⃣ Model Evaluation

* Cross Validation
* Root Mean Squared Error (RMSE)

📈 Results

Random Forest Regressor showed better performance compared to other models after cross-validation.

The pipeline ensures reproducibility and scalability for real-world applications.

 🗂 Project Structure

Californiya_housing_price_predication/
│
├── housing.csv
├── main.py
├──main_old.py
├──input.csv
├──output.csv

🚀 How to Run This Project

1. Clone the repository:
git clone https://github.com/gayatripachpande99/DataScience_miniproject.git

2. Install required libraries:
pip install -r requirements.txt

3. Run the Python file:
python main.py

💡 Key Learnings

* Importance of proper data splitting
* How pipelines simplify ML workflows
* Why preprocessing is crucial before model training
* Comparing models using cross-validation

👩‍💻 Author

**Gayatri Pachpande**
Third-Year Computer Science Student
Aspiring Software Developer | AI & Data Science Enthusiast


