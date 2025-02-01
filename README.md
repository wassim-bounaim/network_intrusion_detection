# 📚 Network Intrusion Detection  

## 📖 Overview  
This project implements an **Artificial Neural Network (ANN)** for detecting network intrusions. It includes **data preprocessing**, model training, and evaluation steps to identify potential threats in network traffic.  

## 📂 Project Structure  
- **`ANN.ipynb`** – Jupyter Notebook containing the ANN model implementation.  
- **`data_preprocessing.ipynb`** – Notebook for cleaning and preprocessing the dataset.  

## 🏗 Model Architecture  
The ANN consists of:  
- **Input Layer**: 35 features  
- **Hidden Layers**: Multiple dense layers with dropout for regularization  
- **Output Layer**: 5 classes (presumably for classification)  

### 🔧 Key Features  
- **Dropout layers** to prevent overfitting  
- **Multiple hidden layers** for deep learning capability  
- **Dense layers** with progressively reduced dimensions  

## 🛠 Installation & Setup  
1. Clone this repository:  
   ```sh  
   git clone https://github.com/your-repo/network-intrusion-detection.git  
   cd network-intrusion-detection  
   ```  
2. Install dependencies:  
   ```sh  
   pip install -r requirements.txt  
   ```  
3. Run the preprocessing script in `data_preprocessing.ipynb`.  
4. Train the model using `ANN.ipynb`.  

## License  
This project is licensed under the MIT License.  
