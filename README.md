# 💊 Drug Classification with Machine Learning

This project uses **Logistic Regression** to classify patients into different drug categories based on medical attributes such as age, sex, blood pressure, and cholesterol levels.  

---

## 📂 Project Structure

├── drug_classification.py # Main script (preprocessing, training, evaluation)
├── drug.csv # Dataset
├── requirements.txt # Dependencies
└── README.md # Project documentation

---

## ⚙️ Requirements

Install dependencies using:

```bash
pip install -r requirements.txt


🚀 How to Run

Clone the repository:

git clone https://github.com/omarfoud/drug-classification.git
cd drug-classification


Run the script:

python drug_classification.py


Output:

Console prints:

Model Accuracy

🔬 Approach

Data Preprocessing:

One-hot encoding of categorical variables (Sex, BP, Cholesterol).

Feature scaling using StandardScaler.

Model: Logistic Regression (max_iter=1000, random_state=42).

Evaluation: Accuracy on test set.

📊 Example Output
Accuracy: 0.85


(Actual accuracy may vary based on train-test split.)

📌 Dataset

The dataset contains medical records with the following features:

Age: Age of the patient

Sex: Male / Female

BP: Blood pressure level (Low, Normal, High)

Cholesterol: Cholesterol level (Normal, High)

Na_to_K: Sodium-to-potassium ratio

Drug: Target variable (Drug type)

🤝 Contribution

Contributions are welcome! Feel free to open an issue or submit a pull request.