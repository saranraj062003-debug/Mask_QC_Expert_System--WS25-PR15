# Mask Manufacturing Quality Control Expert System

## Group Information
**Group Number:** WS25-PR125

### Group Members & Roles
- **Saran Raj Loganathan** – Technical Lead  
- **Mohamed Ameer Kalifulla Khan** – Figures & Presentation  
- **Md Mamunur Rahman** – Report & Documentation  

---

## Project Overview
This project implements a hybrid expert system for automated mask quality control.
The system integrates deep learning, statistical texture analysis, meta-learning,
rule-based reasoning, and explainable AI to detect defective masks in industrial
inspection workflows.

The primary goal of the project is to evaluate the effectiveness of combining
multiple decision-making strategies to improve defect detection accuracy,
interpretability, and operator trust.

---

## Dataset
**Medical Masks Dataset**

- Original dataset provided object-detection annotations.
- Converted into a binary classification task:
  - **Good mask**
  - **Defective mask**
- Conversion enables evaluation of quality inspection methodologies applicable
  to real-world manufacturing environments.

---

## System Architecture
The proposed expert system consists of the following components:

1. **CNN-Based Defect Detection**
   - ResNet-18 architecture
   - Learns visual defect patterns

2. **Histogram-Based Texture Feature Extraction**
   - Captures material uniformity characteristics
   - Includes entropy and uniformity metrics

3. **Meta-Learner Integration**
   - Combines CNN probabilities and texture features
   - Improves overall classification performance

4. **Rule-Based Quality Control Engine**
   - Applies manufacturing-inspired thresholds
   - Enhances interpretability and compliance reasoning

5. **Explainable AI (Grad-CAM)**
   - Visualizes regions influencing defect predictions
   - Improves transparency and operator trust

---

## Research Questions
- **RQ1:** How accurately can a CNN-based model detect defective masks?
- **RQ2:** How effective are histogram-based texture features for material uniformity analysis?
- **RQ3:** How does a meta-learner improve defect detection by combining CNN and texture features?
- **RQ4:** How do rule-based compliance checks enhance interpretability and quality control?
- **RQ5:** How do explainable reasoning charts improve transparency and operator trust?

---

## Results Summary
- CNN model demonstrates strong baseline performance for defect detection.
- Texture features provide complementary information but are insufficient alone.
- Meta-learning significantly improves classification accuracy.
- Rule-based checks enhance decision interpretability.
- Grad-CAM visualizations clearly highlight defect-relevant regions.

Detailed experimental results are available in the `Figures_Tables.zip` file,
organized by research question.

---

## How to Run
1. Open the Jupyter notebook:  
   `Mask_QC_Expert_System.ipynb`
2. Run all cells sequentially from top to bottom.
3. Generated figures and tables will be saved automatically.

---

## Tools & Libraries
- Python
- PyTorch
- OpenCV
- Scikit-learn
- Matplotlib
- Google Colab

---

## Notes
Although the dataset provides binary defect annotations, the project focuses on
evaluating the methodological effectiveness of a hybrid expert system, which can
be extended to fine-grained industrial defect scenarios.
