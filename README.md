# Student Marks Prediction

This Python script uses linear regression to predict student marks based on the number of study hours. It uses the `pandas`, `numpy`, `math`, `matplotlib`, and `scikit-learn` libraries to perform data manipulation, visualization, and modeling.

## Dependencies

Make sure you have the following Python libraries installed:

- pandas
- numpy
- math
- matplotlib
- scikit-learn

You can install them using `pip` if you haven't already:

pip install pandas numpy matplotlib scikit-learn

## Usage

1. Clone or download the repository to your local machine.
   
        https://github.com/tsameema/StudySmartScore

3. Run the script `student_marks_prediction.py`.

        python student_marks_prediction.py
## Methodology
The script will:

1. Load the student data from an online CSV file.
2. Split the data into training and testing sets.
3. Fit a linear regression model to predict student marks based on study hours.
4. Display a scatter plot of the original data and the regression line.
5. Make predictions on the test set and calculate the Mean Squared Error (MSE).
6. Display a scatter plot comparing the actual student marks and predicted marks.
7. Allow you to input a number of study hours to predict the corresponding student marks.
8. After running the script, you will see the predicted score for the given number of study hours.

## Example
    No of Hours = [[9.25]]
    Predicted Score = [93.69173249]
