# Mushroom Classification
Mushroom classification helps determine whether a mushroom is edible or poisonous, ensuring safety in foraging and consumption. By analyzing features like cap shape, gill color, stem dimensions, and season, machine learning models predict the edibility of mushrooms with high accuracy. The process involves cleaning and preprocessing the data, selecting key features, and training classification algorithms to achieve optimal results. 

**Data Source:** https://www.kaggle.com/datasets/prishasawhney/mushroom-dataset


## Team 
- [M. Siri Chandana](https://github.com/siri-chandana-macha)
- [V. Harshitha](https://github.com/)
- [N. Prasanna](https://github.com/)
- [N. Jijnasa](https://github.com/)


## Dataset Overview
The dataset contains the following features:
- **Cap Shape:** Shape of the mushroom's cap.
- **Gill Color:** Color of the gills underneath the cap.
- **Stem Dimensions:** Height and width of the stem.
- **Season:** Seasonal occurrence of the mushroom.

Target Variable:
- **Class:** Binary classification (‘1’ for edible, ‘0’ for poisonous).


## Technologies Used
- Python
- Jupyter Notebook
- pandas, numpy
- scikit-learn
- matplotlib, seaborn



## Approach
1. **Data Preprocessing:**
   - Cleaning and handling missing values.
   - Encoding categorical variables.
2. **Exploratory Data Analysis (EDA):**
   - Visualizing feature distributions and relationships.
3. **Feature Selection:**
   - Identifying the most important features for classification.
4. **Model Training:**
   - Using machine learning algorithms like Logistic Regression, Decision Trees, and Random Forests.
5. **Model Evaluation:**
   - Assessing performance using accuracy, precision, recall, and F1-score.

### Accuracy
- **Overall Accuracy:** 98%

### Classification Report
```plaintext
               precision    recall  f1-score   support

           0       0.99      0.99      0.99      4872
           1       0.99      0.99      0.99      5935

    accuracy                           0.99     10807
   macro avg       0.99      0.99      0.99     10807
weighted avg       0.99      0.99      0.99     10807
```
## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Mushroom_Classification.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Mushroom_Classification
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook mushroom.ipynb
   ```
5. Run the cells to execute the analysis and classification.








