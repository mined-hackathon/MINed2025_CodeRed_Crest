# MINed2025_CodeRed_Crest
# Malware Detection System using ML/AI
![MINeD 2025]

## 🎯 Project Overview
A machine learning-based malware detection system developed during MINeD Hackathon 2025, capable of classifying malware into 7 distinct categories with high accuracy.

### 🏆 Developed at MINeD 2025 Hackathon
- **Event**: MINeD 2025 Hackathon
- **Track**: Securing Systems using ML/AI
- **Organization**: Nirma University & Binghamton University

## ⚡ Features
- Multi-class malware classification
- Real-time detection capabilities
- Comprehensive PE file analysis
- DLL and API call pattern recognition
- Low false-positive rate (<1%)

## 🎯 Malware Categories Detection
1. Benign (0)
2. RedLineStealer (1)
3. Downloader (2)
4. RAT (3)
5. BankingTrojan (4)
6. SnakeKeyLogger (5)
7. Spyware (6)

## 🛠️ Technical Architecture
### Components Analyzed:
- Portable Executable (PE) Headers
- DLL Imports
- API Function Calls

### Technology Stack
- Python 3.8+
- Scientific Libraries:
  - Scikit-learn
  - NumPy
  - Pandas
- Machine Learning Framework:
  - TensorFlow/PyTorch

## 📊 Performance Metrics
- Accuracy: 97%
- Processing Time: <2s per file
- Memory Footprint: <500MB

## 🚀 Getting Started

### Prerequisites
```python
pip install -r requirements.txt
