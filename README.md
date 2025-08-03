# 🔌 Power System Fault Detection and Classification

## 📖 Overview

This capstone project presents a machine learning-based solution to detect and classify faults in electric power distribution systems. The model is trained and deployed on IBM Cloud services and is capable of identifying various types of faults in real time using voltage and current phasor measurements.

---

## 🧠 Problem Statement

Electric power distribution systems are vulnerable to several types of faults such as:

- 🔹 Line-to-ground faults  
- 🔹 Line-to-line faults  
- 🔹 Three-phase faults  

Traditional fault detection systems lack real-time classification accuracy, especially under dynamic grid conditions. This leads to delays in response and extended outages.

---

## 💡 Proposed Solution

We propose a fault classification system that leverages **machine learning (ML)** and **IBM Watson Studio** to accurately classify different fault types using real-time data.

### 🔍 Key Features

- Real-time classification of faults  
- Hosted on IBM Cloud for scalable deployment  
- Uses voltage and current phasor data as input  

---

## ⚙️ System Architecture

### 🧩 Components

- **Data Collection**: Phasor measurement data (Voltage, Current)
- **Feature Extraction**: Signal processing techniques
- **Model Training**: ML classifier using labeled fault data
- **Deployment**: Model hosted with API on IBM Watson Studio

### 📊 ML Algorithm

- **Classifier**: Random Forest (or SVM depending on performance)
- **Frameworks**: Scikit-learn, TensorFlow  
- **Cloud Services**:
  - IBM Watson Studio (for training and deployment)
  - IBM Cloud Object Storage (for dataset handling)

---

## 🚀 Result

The model successfully classifies faults in real time and shows:
- Higher accuracy than traditional systems  
- Reduced fault response time  
- Scalability via cloud deployment  

---

## 🔭 Future Scope

- 🔌 Extend to **transmission grid** level faults  
- 🌐 Integrate with **real-time IoT sensors**  
- 🧠 Use **deep learning (e.g., LSTM)** for temporal fault patterns  
- 🔧 Add **predictive maintenance** functionality  

---

## 📚 References

- IEEE papers on power system fault detection  
- IBM Cloud & Watson Studio documentation  
- Scikit-learn, TensorFlow libraries  
- Research on phasor measurement unit (PMU) data analysis  

---

## 🏷️ Author

**Atharva Pate**  
MIT Academy of Engineering  
Department of Computer Engineering

---

## 📜 License

This project is for academic and research use. Please cite accordingly if used.

