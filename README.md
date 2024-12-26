# Using-Regression-and-Classification-to-Predict-Income-from-OkCupid-Profile-Features

Objective:
The goal of this project was to analyze OkCupid profile data to predict users’ income and classify income brackets based on profile features using machine learning techniques.

Analysis and Methods
	1.	Regression Analysis:
	•	Question: Can income be predicted using essay length (essay_len) and average word length (avg_word_len) from user essays?
	•	Models Used: Linear Regression and K-Nearest Neighbors Regression.
	•	Results:
	•	Both models performed poorly, with high Mean Squared Error (MSE) and negative R² scores.
	•	The results suggest that essay characteristics alone are insufficient predictors of income.
	•	Conclusion: Text features like essay length and word length lack strong correlation with income.

	2.	Classification Analysis:
	•	Question: Can income brackets be classified using education and body type as features?
	•	Models Used: Logistic Regression and Random Forest Classifier.
	•	Results:
	•	Both models achieved low accuracy (~20%) and struggled with precision and recall across income brackets.
	•	Class imbalance (dominance of the “nan” class) further reduced performance.
	•	Conclusion: Education and body type alone were not strong predictors for income brackets.
