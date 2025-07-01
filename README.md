
# 🗑️ Garbage Classification using Machine Learning and Computer Vision

This project uses **Convolutional Neural Networks (CNNs)** along with **transfer learning** to automatically classify garbage into 7 categories:  
**Cardboard, Compost, Glass, Metal, Paper, Plastic**, and **Trash**.

---

## 📌 Objective  
To develop an AI-powered image classification system that automates garbage sorting and supports smart waste management solutions.

---

## 📂 Dataset  
- **Total Images:** 2,187  
- **Classes:** 7 waste categories  
- **Source:** [Google Drive Dataset](https://drive.google.com/drive/folders/1IHlDN1oXhsnb9xAwUOQJrfJ3s83mkDeg)  
- **Structure:** Split into `train/` and `test/` directories

---

## 🧠 Models Used  
- **VGG16** (Transfer Learning)  
- **ResNet50** (Transfer Learning)  
- **Libraries:** TensorFlow, Keras, OpenCV, Matplotlib

---

## ⚙️ Methodology  
- Image preprocessing (resizing, normalization) and data augmentation  
- Applied transfer learning with frozen base CNN layers  
- Trained models with EarlyStopping and ModelCheckpoint  
- Evaluated using accuracy/loss graphs and prediction samples

---

## ✅ Results  
- **Training Accuracy:** ~88%  
- **Validation Accuracy:** ~75%  
- Successfully classified unseen waste images with good generalization

---

## 📸 Sample Outputs  
- Accuracy and loss plots  
- Sample image predictions with classified output

---

## 🚀 Future Scope  
- Real-time integration in **smart bins** or **mobile apps**  
- Training with larger, more diverse datasets  
- Deployment in **public or industrial waste management systems**

---

## ▶️ How to Run  

```bash
# Clone the repository
git clone https://github.com/yourusername/garbage-classification-ml.git

# Navigate to project folder
cd garbage-classification-ml

# Install dependencies
pip install -r requirements.txt

# Train the model
python train_vgg16.py

# OR test a trained model
python predict.py --image path/to/image.jpg
```

---

## 🙌 Acknowledgements  
- Transfer learning models from **Keras Applications**  
- Dataset curated manually from open sources  
- Graphs and visualizations created using **Matplotlib** and **VisualKeras**
