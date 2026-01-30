# Task 10: KNN – Handwritten Digit Classification
## 📌 Internship: AI & ML Internship  
**Task Number:** 10  
**Algorithm Used:** K-Nearest Neighbors (KNN)

## 📖 Problem Statement

The objective of this task is to implement **handwritten digit classification** using the **K-Nearest Neighbors (KNN)** algorithm.
The model classifies digits (0–9) based on distance between data points and predicts the class of unknown digits.

## 📊 Dataset

**Primary Dataset:**  
- Sklearn Digits Dataset (`load_digits()`)

**Dataset Details:**
- Total samples: 1797
- Image size: 8 × 8 pixels
- Features: 64
- Target classes: Digits 0–9

## 🛠 Tools & Libraries Used

- Python  
- NumPy  
- Matplotlib  
- Scikit-learn
  
## ⚙️ Steps Performed

1. Loaded the digits dataset using `load_digits()`
2. Checked shape of features and labels
3. Visualized digit images using matplotlib
4. Split dataset into training and testing sets
5. Applied feature scaling using **StandardScaler**
6. Trained KNN model with **K = 3**
7. Tested multiple K values: **3, 5, 7, 9**
8. Calculated accuracy for each K
9. Plotted **Accuracy vs K graph**
10. Selected best K value
11. Generated **confusion matrix**
12. Displayed sample test images with predicted labels

## 📈 Accuracy Results

| K Value | Accuracy |
|--------|----------|
| 3 | High |
| 5 | Better |
| 7 | Optimal |
| 9 | Slight decrease |

> Best K was selected based on highest accuracy.

## 📊 Outputs

### ✅ Accuracy vs K Plot
Shows how accuracy changes with different K values.

### ✅ Confusion Matrix
Helps analyze correctly and incorrectly classified digits.

### ✅ Final Prediction Output
Displays test images along with predicted digit labels.

## 🧠 Concepts Learned

- Distance-based classification
- Importance of feature scaling in KNN
- Effect of K value on bias–variance tradeoff
- Confusion matrix interpretation
- Hyperparameter tuning

## ❓ Interview Questions Covered

- What is K in KNN?
- Why is feature scaling required in KNN?
- What is Euclidean distance?
- What happens when K is too small or too large?
- What are limitations of KNN?

## 📌 Conclusion

The KNN algorithm successfully classified handwritten digits with good accuracy.  
By tuning the value of K and applying proper scaling, model performance improved significantly.
This task helped in understanding **distance-based machine learning algorithms** and their practical implementation.
