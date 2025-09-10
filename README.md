# Brain Tumor Classification 🧠
This project was developed as part of my Deep Learning mid exam. It was my first time working with image datasets, specifically brain MRI scans, to classify tumor types. The main focus is not only accuracy, but also recall, especially for malignant cases such as glioma.

## ✨ Project Overview  
- **Goal**: Classify MRI brain images into four categories:  
  - Glioma  
  - Meningioma  
  - Pituitary  
  - No Tumor  
- **Baseline Model**: CNN with 79% accuracy  
- **Tuned Model**: CNN with 84% accuracy  
- **Key Insight**: Recall is the most critical metric in the medical context, especially for detecting malignant tumors.  

## 📊 Key Findings  
- **Glioma**: High precision but lower recall. Some cases misclassified as meningioma → risk of delayed treatment.  
- **Meningioma**: Moderate precision & recall. Sometimes misclassified as no tumor.  
- **No Tumor**: High recall & precision. Model performs well here, likely due to more samples.  
- **Pituitary**: High recall & precision, but less critical than glioma recall.  

⚠️ **Medical context**: Accuracy alone isn’t enough. Improving recall for glioma is essential since it’s the most malignant tumor type.  

## 🛠️ Tech Stack  
- Python  
- TensorFlow/Keras  
- Google Colab (GPU)  

## 🚀 Future Improvements  
- Expand dataset (especially on glioma cases)  
- Class weight adjustments to handle class imbalance  
- Data augmentation (brightness/contrast tuning for glioma images)  
- Try other architectures (e.g., ResNet, EfficientNet) — limited GPU prevented full runs  

## 📷 Example Results  
<img width="721" height="539" alt="image" src="https://github.com/user-attachments/assets/3507c399-4183-4187-ad9b-bdd2c5a6d945" />
<img width="532" height="490" alt="image" src="https://github.com/user-attachments/assets/ff7f233b-ded3-4aa8-bbb0-ad3e93764dd4" />

## 👩‍💻 Author  
**Michelle Nathania**  
Data Science student at BINUS University | Interested in Machine Learning and Deep Learning
