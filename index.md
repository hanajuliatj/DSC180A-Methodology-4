---
layout: default
title: "Methodology 4 - Hana Tjendrawasi"
---

# DSC180A - Methodology 4
**Name:** Hana Tjendrawasi<br>
**Email:** htjendrawasi@ucsd.edu<br>  
**Section:** B15 - Differentially private synthetic telemetry data with modern generative AI<br>  
**Mentor:** Professor Yu-Xiang Wang

---

### **1. What is the most interesting topic covered in your domain this quarter?**
The most interesting topic is that differentially private synthetic data generation plays a crucial role in enabling data sharing and analysis while preserving individual privacy. By creating artificial datasets that statistically resemble real data without revealing any specific individual's information, this approach allows organizations to comply with privacy regulations such as GDPR and HIPAA. It fosters innovation and collaboration by making sensitive data accessible to researchers, developers, and analysts without exposing personal details. This balance between utility and privacy is essential for advancing fields like healthcare, finance, and social science in a responsible and ethical manner.

### **2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**
I'm interested in investigating how differential privacy can be applied to image datasets, specifically, generating differentially private synthetic photo albums using hierarchical or multimodal generative models. I'd like to analyze how privacy noise affects model fidelity and realism, and whether combining textual metadeta with visual data improves the trade-off between privacy and utility.

### **3. What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**
In Quarter 1, our approach relied primarily on DP-SGD for privacy preservation. For Quarter 2, I'd like to explore incorporating post-processing techniques such as Private Evolution, which optimizes the synthetic dataset after generation to improve quality without violating the DP guarantee. I'd also consider automating hyperparameter tuning to systematically explore privacy ε-δ trade-offs.

### **4. What other techniques would you be interested in using in your project?**
I'd like to experiment with diffusion models and large multimodal architectures like Stable Diffusion or Gemini for cross-modal synthesis. I'm also curious about clustering and feature compression to reduce sensitivity before applying DP noise, as well as integrating evaluation metrics like FID and privacy-utility curves to quantitatively measure trade-offs.
