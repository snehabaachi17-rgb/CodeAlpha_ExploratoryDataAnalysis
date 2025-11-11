Exploratory Data Analysis on the Iris Dataset

CodeAlpha Internship – Task 2

📘 Overview

This project performs Exploratory Data Analysis (EDA) on the famous Iris dataset, which contains measurements of:

Sepal Length

Sepal Width

Petal Length

Petal Width

Species (Setosa, Versicolor, Virginica)


The goal is to understand patterns, relationships, and distributions in the data using visualizations.


---

🗂 Project Structure

├── CodeAlpha_ExploratoryDataAnalysis.ipynb
├── visuals/
│   ├── sepal_length_boxplot.png
│   ├── sepal_length_distribution.png
│   ├── correlation_heatmap.png
│   ├── pairplot.png
│   └── ...
├── requirements.txt
└── README.md


---

📊 Analysis Performed

✔ Data Loading
✔ Summary statistics
✔ Distribution plots
✔ Boxplots for each feature
✔ Correlation heatmap
✔ Pairplot for species comparison
✔ Insights from visuals


---

🔍 Key Insights

Petal length and petal width show clear separation between species.

Setosa is easily separable due to lower petal measurements.

Sepal features overlap more and are less useful for classification.

Strong positive correlation between petal length & petal width.



---

🛠 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn



---

▶ How to Run

1. Install dependencies:

pip install -r requirements.txt


2. Open the notebook:

jupyter notebook CodeAlpha_ExploratoryDataAnalysis.ipynb




---

📌 Conclusion

The Iris dataset clearly shows species-level separation through petal-based features.
The visuals confirm strong patterns that can be used for ML classification.
