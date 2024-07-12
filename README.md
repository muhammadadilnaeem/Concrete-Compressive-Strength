
---

# **Concrete Compressive Strength Prediction**

<h1 style="font-family: 'poppins'; font-weight: bold; color: Blue;">Author: Muhammad Adil Naeem</h1>

[![GitHub](https://img.shields.io/badge/GitHub-Profile-green?style=for-the-badge&logo=github)](https://github.com/muhammadadilnaeem) 

[![Twitter/X](https://img.shields.io/badge/Twitter-Profile-red?style=for-the-badge&logo=twitter)](https://twitter.com/adilnaeem0) 

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/muhammad-adil-naeem-26878b2b9/)  

## **Project Overview**

This project aims to predict the compressive strength of concrete using various machine learning models. The analysis is performed on a dataset that includes features such as the composition and age of the concrete. The goal is to identify the most effective model for predicting concrete strength.

## **Table of Contents**

- [**Concrete Compressive Strength Prediction**](#concrete-compressive-strength-prediction)
  - [**Project Overview**](#project-overview)
  - [**Table of Contents**](#table-of-contents)
  - [**Project Structure**](#project-structure)
  - [**Dataset**](#dataset)
  - [**Exploratory Data Analysis**](#exploratory-data-analysis)
  - [**Modeling**](#modeling)
    - [**Best Model**](#best-model)
  - [**Key Findings**](#key-findings)
  - [**Possible Flaws and Future Work**](#possible-flaws-and-future-work)
  - [**How to Run**](#how-to-run)
  - [**Contributing**](#contributing)
  - [**License**](#license)

## **Project Structure**

- `data/`: Contains the dataset used for the analysis.
- `notebook/`: Jupyter notebooks with the data exploration, cleaning, and clustering models.
  
## **Dataset**

The dataset used in this project contains the following features:

- Cement
- Blast Furnace Slag
- Fly Ash
- Water
- Superplasticizer
- Coarse Aggregate
- Fine Aggregate
- Age (in days)
- Concrete Compressive Strength (target variable)

The dataset is complete with no missing values.

## **Exploratory Data Analysis**

The key steps in the exploratory data analysis include:

- Descriptive statistics and distribution plots.
- Correlation analysis to understand the relationships between features.
- Visualization of the concrete compressive strength against various features.

## **Modeling**

Several machine learning models were evaluated to predict concrete compressive strength, including:

1. **Linear Regression**
2. **Decision Tree**
3. **Random Forest**

### **Best Model**

The best-performing model is the **Random Forest** with an accuracy of **0.912621359223301**. This model captures the nuances of the data more effectively compared to simpler models like Linear Regression.

## **Key Findings**

- The concrete compressive strength varies significantly based on the composition and age of the concrete.
- Complex models like Random Forest tend to perform better than simpler models.

## **Possible Flaws and Future Work**

- The dataset might have some multicollinearity, which could affect the performance of some models.
- Further feature engineering and selection might improve model performance.
- Additional data, especially with more varied compositions and conditions, could provide better generalization.

## **How to Run**
1. Clone the repository:
   ```bash
   git clone https://github.com/muhammadadilnaeem/Concrete-Compressive-Strength.git
   cd Concrete-Compressive-Strength
   ```
2. Create and activate a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook notebook/Concrete_Compressive_Strength.ipynb
   ```

## **Contributing**

Contributions are welcome! Please fork the repository and submit a pull request for review.

## **License**

This project is licensed under the MIT License - see the [LICENSE](https://github.com/muhammadadilnaeem/Concrete-Compressive-Strength/blob/main/LICENSE) file for details.

---