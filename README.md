# Network Intrusion Detection System: Anomaly and Attack Classification Using Machine Learning

**Business Context**:  
With the growth of computer networks, security vulnerabilities are increasingly challenging to address, making **Intrusion Detection Systems (IDS)** crucial for detecting network anomalies and attacks. This project aims to develop a network intrusion detection system using machine learning.

**Objectives**:  
1. **Binomial Classification**: Identify if a network activity is "Normal" or an "Attack."
2. **Multinomial Classification**: Detect the specific type of attack (e.g., Back, Smurf, Root Kit, etc.).

**Available Data**:  
- Data consists of 10 files representing different types of attacks and normal network activity.  
- Features include time, content, and host-based traffic data, covering aspects like duration, protocol, source/destination bytes, login status, and error rates.  
- Data types include nominal, binary, and numeric values.

**Key Tasks**:  
1. **Data Preparation**:
   - Append all files and add an "attack" column based on attack type.
   - Handle class imbalance through resampling.
   - Create separate labels for binomial and multinomial classification.
2. **Model Development**:
   - Train machine learning models for both classifications using the prepared dataset.
   - Address data imbalance issues during training.

**Expected Output**:  
- Intrusion detection models with robust performance.  
- Accurate classification of network activity into normal or specific attack categories.  
- Insights into key features contributing to network anomalies.
