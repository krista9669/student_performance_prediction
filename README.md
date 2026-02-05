Student Performance Prediction

This project predicts a student’s final grade using basic machine learning techniques. It uses past academic performance and study-related features to 
build a regression model and evaluate how accurately it can estimate final scores.

Dataset (separated by commas ;)
The project uses a student performance dataset containing information such as:
- Study time
- Number of absences
- Previous grades (G1, G2)
- Final grade (G3)

Approach
- load the dataset using pandas
- select relavent features for calculation like study time and previous grades
- split dataset into training and testing
- scale features
- trained a linear regression model
- evaluated performance using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE)

Output
The script prints:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
These metrics show how close the predicted grades are to the actual final grades

What I Learned
- How to build an end-to-end machine learning pipeline
- How to evaluate regression models using appropriate metrics
