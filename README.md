# ML/DL Projects

1. Fake News Detection using Word2Vec

Built a semantic classification system to identify fake news articles using Word2Vec embeddings and ensemble learning.

Problem: Misinformation detection at scale for digital platforms

Implementation:
- Word2Vec embeddings for semantic text representation
- Ensemble approach with Random Forest, Logistic Regression, and SVM
- TF-IDF weighted document embeddings
- Handled class imbalance and feature engineering challenges

Results: 94% accuracy, 93% F1-score. Ensemble methods outperformed individual classifiers.

Stack: Python, Gensim, Scikit-learn, NLTK, Pandas

2. Named Entity Recognition using CRF

Developed a sequence labeling system using Conditional Random Fields to extract named entities from unstructured text.

Problem: Automated information extraction for document processing

Implementation:
- CRF model with IOB tagging for entity boundaries
- Feature engineering: word shape, POS tags, context windows
- Multi-class classification (Person, Organization, Location, Date)
- Parameter optimization for sequence labeling

Results: 91% accuracy, 90% F1-score. Competitive performance with deep learning approaches.

Stack: Python, sklearn-crfsuite, NLTK, spaCy

3. Waste Segregation using CNN

Computer vision system for automated waste classification using CNNs and transfer learning.

Problem: Automated waste sorting for recycling facilities

Implementation:
- CNN architecture with transfer learning (VGG16, ResNet50, MobileNet)
- Multi-class classification: plastic, paper, metal, glass, organic
- Data augmentation for limited training samples
- Optimized for real-time inference

Results: 96% accuracy, 95% F1-score. Transfer learning reduced training time by 70%.

Stack: Python, TensorFlow/Keras, OpenCV, NumPy

## Performance

| Project | Accuracy | F1-Score |
|---------|----------|----------|
| Fake News Detection | 94% | 93% |
| Named Entity Recognition | 91% | 90% |
| Waste Segregation | 96% | 95% |
