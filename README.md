# CS 6140 (Machine Learning) - Final Project Summary

## Performance Analysis and Decision Making in Football using Event and Tracking Data

**Data:** Event and tracking data provided by MCFC partners Second Spectrum and StatsBomb from 6 WSL games  
[Event and Tracking Data](https://drive.google.com/drive/folders/1cGrTtDJXq5otTa-mh2sB4ApTdjKMcwk7)

**Approach:** Use machine learning algorithms to analyze player and team performance based on event and tracking data to identify patterns and insights that can inform decision making.

**Tools/libraries:** Python, Pandas, NumPy, scikit-learn, Matplotlib, Seaborn

**Models:** Clustering, Classification, Regression, Deep Learning (CNNs, RNNs)

### Steps

1. **Data Cleaning and Preparation:** 
   - Clean and preprocess the event and tracking data.
   - Combine the data from both sources, and prepare it for analysis.

2. **Feature Engineering and Selection:** 
   - Create new features and select the most relevant ones to use in the models, such as distance covered, passes completed, shots on target, player positioning, etc.

3. **Model Building and Training:** 
   - Build and train machine learning models to analyze player and team performance based on the selected features, such as clustering players based on their playing style, classifying successful vs. unsuccessful passes, or regressing the number of goals scored based on various factors.
   - Use deep learning models like convolutional neural networks (CNNs) or recurrent neural networks (RNNs) to analyze tracking data sequences over time.

4. **Model Evaluation and Interpretation:** 
   - Evaluate the performance of the models using cross-validation and interpret the results to gain insights into player and team performance that can inform decision making, such as identifying players who are underperforming or overperforming, assessing the effectiveness of different tactics, or predicting the outcome of future games.
   - Use techniques like saliency mapping or activation maximization to understand what features the deep learning models are focusing on.

5. **Visualizations/results:** 
   - Heat maps, scatter plots, confusion matrices, accuracy and loss plots, feature importance graphs, saliency maps, activation maximization, etc.
