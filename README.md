# Eczema-Detection-Classifier-AD-vs-Eczema-
## Project overview
This repository contains a CNN-based image classification project focused on distinguishing eczema from atopic dermatitis. The model is inspired by EczemaNet and is used to analyze model behavior, misclassifications, and decision boundaries rather than to provide clinical diagnosis.

### Methodology
- Transfer learning using a pretrained CNN backbone
- Class weighting and threshold tuning to address imbalance
- Grad-CAM for model explainability and error analysis
  
### Key Insights
- Visual overlap is the main source of misclassification
- Model errors are systematic and explainable
- Performance improvements involve trade-offs between sensitivity and specificity

### Repository Structure
- DermaTrace_project.pptx – Project presentation summarizing the problem, approach, and results
- DermaTrace_project(final).ipynb – Main notebook containing data preparation, model training, evaluation, and explainability
- Research Document-EczemaNet project.pdf – Research document providing background, methodology, analysis, and conclusions
- app.py – Streamlit application for demonstrating the trained model and Grad-CAM visualizations
- app.link – Link to the deployed Streamlit demo
- README.md – Project overview, methodology, and key Insights

### Disclaimer
This project is for educational and research purposes only and does not provide medical diagnosis.

