🍃 **Rice Leaf Disease Prediction** 🌾


# Rice Leaf Disease Prediction  

## 📌 Project Overview  
Rice Leaf Disease Prediction is an AI-powered tool designed to detect rice crop diseases early using deep learning models.  
This system helps farmers by analyzing images of rice leaves and classifying them into six categories:  
- Bacterial Leaf Blight  
- Brown Spot  
- Healthy Leaf  
- Leaf Blast  
- Leaf Scald  
- Narrow Brown Spot  

### Key Features  
- Uses CNN, MobileNetV2, and ResNet models for high accuracy  
- Provides real-time disease predictions via a Gradio interface  
- Suggests preventive actions for better crop management  
- Runs on Google Colab for easy accessibility  

### Impact on Agriculture  
By leveraging AI-powered disease detection, farmers can make informed decisions, reduce crop losses, and promote sustainable agriculture.  
This tool makes disease identification faster, more reliable, and accessible to farmers with minimal technical knowledge.  

---

## 🛠️ How to Run  
1. Open your Google Colab notebook (`ricecropdiseaseprediction.ipynb` for training & `miniproject.ipynb` for interface).  
2. Ensure all required models (`cnn_model.h5`, `mobilenet_model.h5`, `resnet_model.h5`) are stored in Google Drive.  
3. Mount Google Drive in the Colab notebook using:  
   ```python
   from google.colab import drive
   drive.mount('/content/drive')


### 📂 Project Files

📜 `ricecropdiseaseprediction.ipynb` → Model training & preprocessing  
📜 `miniproject.ipynb` → Gradio interface for predictions  
📜 `mobilenet_model.h5` → MobileNet model (used for classification)  
📜 `cnn_model.h5` → CNN model for disease prediction  
📜 `resnet_model.h5` → ResNet model for feature extraction  
📜 `docs/` → Project documentation (Word & PDF)  
📜 `resources/` → Research papers, PPTs, and related literature


### 📑 Usage Guide 

> Upload a **clear rice leaf image** in the Gradio interface.  
> The AI model predicts the **disease type** based on deep learning classification.  
> It suggests **prevention tips** tailored for each disease.  
> Users can test multiple images to **validate accuracy**.  
> Follow recommended actions to ensure better **crop management**.




### 🔹 Best Practices for Better Accuracy
- Use **high-quality images** with good lighting.  
- Ensure the leaf is **clearly visible** without background interference.  
- Try **multiple angles** for better detection.  

### 🔹 Troubleshooting Errors
❌ **Issue:** No prediction appears?  
✔️ **Fix:** Ensure model files (`mobilenet_model.h5`, `cnn_model.h5`, `resnet_model.h5`) are available in Google Drive.  

❌ **Issue:** Incorrect classification?  
✔️ **Fix:** Try uploading a **clearer image with better lighting & resolution**.  

❌ **Issue:** Execution stops in Google Colab?  
✔️ **Fix:** Restart runtime and **rerun all cells** sequentially.








