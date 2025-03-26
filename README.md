# 🚨 Phishing URL Identification  

This repository contains a Jupyter Notebook for detecting phishing URLs using machine learning. The notebook preprocesses URL data, extracts features, and trains multiple models to classify URLs as legitimate or phishing.  

## 📌 Features  
- **Data Preprocessing**: Cleans and extracts meaningful features from URLs.  
- **Feature Engineering**: Converts URLs into structured numeric data.  
- **Machine Learning Models**: Implements multiple models for classification.  
- **Model Evaluation**: Assesses models using accuracy, precision, recall, and F1-score.  
- **Hugging Face Integration**: Uses Hugging Face models and requires authentication.  

## 🛠 Models Used  
The notebook explores different machine learning models, including:  
✅ Logistic Regression  
✅ Random Forest  
✅ XGBoost  
✅ Deep Learning Models (if applicable)  

## 🔧 Installation & Setup  
Ensure you have the required dependencies installed:  

```bash
pip install pandas numpy scikit-learn xgboost transformers datasets
```

For Hugging Face integration, log in using:  

```python
from huggingface_hub import notebook_login
notebook_login()
```

## 🚀 Usage  
1. Open the notebook in **Jupyter** or **Google Colab**.  
2. Run the cells step by step for data preprocessing, model training, and evaluation.  
3. Modify hyperparameters or add custom models for further experimentation.  

## 📢 Contributing  
Feel free to submit issues or pull requests to enhance the project.  

## 📜 License  
This project is licensed under the **MIT License**.  
