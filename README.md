# machine-learning-challenge

I chose 2 machine learning models to analyze the exoplanet_data.csv: Logical Regression Model and SVM Model

Both models follow the same overview below:

    a. Selected features
    b. assinged y to koi_disposition column
    c. assigned X to every other column in the dataset
    d. Performed train_test_split to plit dataset
    e. Performed preprocessing using the MinMaxScaler
    f. Trained the model:
        Logical Regression Scores:
            Training Data Score: 0.8472248712569139
            Testing Data Score: 0.8638443935926774

        SVM Scores:
        Training Data Score: 0.7774175090596986
        Testing Data Score: 0.7774599542334096

    g. Performed Hyperparameter Tuning
        
        Logical Regression 
        best parameters: 'C': 0.1, 'multi_class': 'auto"
        best score: 0.6788086072522722

        SVM 
        best parameters: 'C': 50, 'gamma': 0.0001
        best score: 0.8207120194441817

    Conclusion: Based on the scores, the Logical Regression model is better at predicting new exoplanets with 86% accuracy.  Hyperparamter tuning casused this score to drop to 67.8%.

    What could make the model better?  Perhaps more data for either model would make the predictions more accruate.
     




