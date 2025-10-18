# Emotion Recognition from Text (NLP)

This project is a **deep learning model** that can recognize human emotions from short text sentences. It uses a large NLP dataset and a **Bidirectional LSTM (BiLSTM)** architecture to classify text into one of six emotion categories.


## Dataset

**Source:** [Sentiment and Emotion Analysis Dataset on Kaggle](https://www.kaggle.com/datasets/kushagra3204/sentiment-and-emotion-analysis-dataset)  

Total samples: ~420,000  
  - Joy: 143,067 samples  
  - Sadness: 121,187 samples  
  - Anger: 59,317 samples  
  - Fear: 49,649 samples  
  - Love: 34,554 samples  
  - Surprise: 14,972 samples  

The dataset contains two columns:  
- `sentence`: the text input  
- `emotion`: the labeled emotion  


## Requirements

**Python version:** 3.11 or higher  

**Libraries used:**

```bash
pandas
numpy
matplotlib
seaborn
tensorflow
scikit-learn
```

## Results
- Achieved ~94% validation accuracy on the test set.
- Can predict the probability of each emotion (e.g., joy: 0.91, sadness: 0.02, etc...)

## Contributing
Contributions are welcome! If you find any mistakes or have suggestions for improvement, please contact me or open an issue