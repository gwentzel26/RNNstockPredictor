# **Predicting the Price of Disney Stock using Recurrent Neural Networks**
  
## **Description**
      
  Create a general outline predicting future stock price movement of Disney to develop a trade entry and exit strategy using Recurrent Neural Networks.
      
## **Table of Contents** 
      
  - [Dataset](#dataset)
  - [Libraries](#libraries)
  - [Results](#results)
  - [Contributions](#contributions)
  - [Attachments and Contact](#attachments)
      
## **Dataset <a id="dataset"></a>**
  
    Source: Kaggle.
    Content: Historical stock prices of Disney from 1999 to October 2024.
    Variables: Open Price, Close Price, High Price, Low Price, Volume
    Format: CSV file imported as a Pandas DataFrame for analysis.
    Focus:
    Used high prices to predict the next high price using a
    Long Short Term Memory and Gated Recurrent Unit

      
## **Libraries <a id="libraries"></a>**

    Python: Primary programming language for the project.
    NumPy: Numerical computations.
    Pandas: Data manipulation and preprocessing.
    Matplotlib: Data visualization.
    Scikit-learn: Data scaling and evaluation metrics.
    TensorFlow: Building and training the RNN model

## **Results <a id="results"></a>**

    The RNN model successfully captured the overall trend in Disney's stock price movements.
    Despite the irregular shape and noise in the distribution of data points, the model was able to predict a fairly accurate shape for future high prices.
    Highlights the model's strength in learning patterns from complex, non-linear time-series data.
    Minor deviations in individual predictions were observed, likely due to market volatility and random fluctuations

      
## **How to Contribute <a id="contributions"></a>**
      
  Download our python file and use whatever data you'd like!
      
  
      
## **Attachments and Contact <a id="attachments"></a>**
      


  I have attached two presentations in this repository. One for our 25 minute lecture on how Recurrent Neural Networks work and the different types/applications there are, and another on our specific Stock predictor.

    Please feel free to reach me at gwentzel@binghamton.edu or on linked in at "https://www.linkedin.com/in/gavinwentzel/"
