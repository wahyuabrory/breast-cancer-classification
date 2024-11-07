# 🤖 Breast Cancer Prediction with TensorFlow.js 🤖

## 🚀 Getting Started

Clone the repository: 
```bash
git clone https://github.com/wahyuabrory/breast-cancer-prediction.git
```

Navigate to the project directory: 
```bash
cd breast-cancer-prediction
```

Run the model: Open 
```bash
index.html 
```
in a local server to run the model training and see the results printed in the console.

Download the model: 
```bash
After training, the model will be automatically saved as my_model in your downloads.
```

## 📈 Model Architecture
This model uses a simple neural network with the following architecture:

- Input layer with 30 features
- Hidden layers with 64, 32, and 16 units respectively, using ReLU activation
- Output layer with 1 unit and Sigmoid activation for `binary classification`

## 📊 Training Parameters
- **Epochs**: 100
- **Batch size**: 32
- **Loss function**: Binary Crossentropy
- **Optimizer**: RMSProp

## 🗃️ Datasets
The data is loaded from `wdbc-train.csv` and `wdbc-test.csv`, which should be structured in the following way:

- **Features**: 30 columns of features
- **Label**: diagnosis column, representing the target classification label


## 🗒️ Logging
During training, the `console logs` the loss and accuracy for each epoch, helping you monitor the model's performance.

---

## 🔗 Useful Resources

- [TensorFlow.js Documentation](https://www.tensorflow.org/js)
- [Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))





