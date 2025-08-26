# Early Prediction of Diabetes

A real-time diabetes prediction system leveraging patient medical records.

---

 Highlights:
- **Combines multiple algorithms**—Support Vector Machine (SVM), Artificial Neural Network (ANN), and fuzzy logic—to enhance predictive accuracy and reliability.
- **Improves performance** by algorithm fusion, overcoming limitations of individual models.

---

##  Features

| Feature | Description |
|--------|-------------|
| **Multi-model fusion** | Integrates SVM and ANN with fuzzy logic for robust predictions. |
| **Real-time inference** | Fast model predictions suitable for real-time applications. |
| **Accuracy-focused** | Fusion strategy boosts overall prediction reliability. |
| **Extensible** | Easy to experiment with different model combinations and datasets. |

---

##  Getting Started

### Prerequisites

- Python 3.7 or later  
- Jupyter Notebook or similar environment  
- Dependencies:  
  ```bash
  pip install numpy pandas scikit-learn
  ```

---

### Usage

1. Open `Diabetes_Prediction.ipynb` in Jupyter.
2. Load the dataset: `diabetes_dataset.csv`.
3. Preprocess data (handle missing values, normalization, encoding).
4. Train and evaluate:
   - **SVM Model**
   - **ANN Model** (e.g., via TensorFlow/Keras)
   - **Fuzzy Logic Integration** (for final decision fusion)
5. Compare results to observe enhanced performance through fusion.

---

##  How It Works

1. **Baseline models**: Train SVM and ANN separately on the medical dataset.
2. **Fuzzy logic integration**: Use fuzzy rule-based aggregation to combine model predictions, improving decision stability and accuracy.
3. **Performance evaluation**: Compare individual versus fused-model metrics.

---

##  Performance Highlights

- **Improved accuracy & reliability** through multi-algorithm fusion.
- **Real-time capabilities** via optimized inference logic.
- **Versatile framework** enabling experimentation with alternative models or fusion strategies.

---
