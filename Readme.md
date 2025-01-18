![iStock-804619352](https://github.com/rbhardwaj2186/SBA-Loan-Risk-Modelling/assets/143745073/179fb7ad-8b23-413f-9713-f227945bd62d)

# SBA Loan Default Prediction System

## Project Overview
End-to-end machine learning system to predict loan defaults from the Small Business Administration (SBA) dataset using multiple modeling approaches. The system utilizes advanced feature engineering, model optimization techniques, and machine learning interpretability methods to achieve high prediction accuracy while maintaining model explainability.

## Key Achievements
- 86% AUCPR score on test dataset
- 30% reduction in false positives through threshold optimization
- Processing capability of 800K+ transaction records
- Sub-100ms inference time per prediction
- Advanced model interpretability using SHAP values

## Project Structure
```python
├── Project-1-starter-v0.ipynb     # Initial model development and EDA
├── SBA_Light_GBM_Optuna.ipynb     # Advanced LightGBM model with optimization
├── Scoring.ipynb                  # Production scoring pipeline
├── best_params.pkl               # Serialized model parameters

Is it better to approve or deny this loan?
An upvote would be appreciated if you download the data set and like it.

In order to help small firms get loans, the Small Business Administration (SBA) was established in 1953. In the US, small companies have historically been the main employer. Aiding small companies contributes to the development of jobs, which lowers unemployment. Growth of small businesses helps the economy expand as well. The SBA offers bank loan guarantees as one of its assistance programs for small companies. By lowering their risk, banks are encouraged to lend to small firms thanks to this assurance. The bank loses money on the remaining amount if the loan defaults, and the SBA pays the guaranteed amount.



## Project SBA Loan Risk Modelling Guidelines


**Here are some tips for submitting your project. You can use the points as partial check list before submission.**

- **Give your notebook a clear and descriptive title.** 
- **Explain your work in Markdown cells.** This will make your notebook easier to read and understand. You can use different colors of font to highlight important points.
- **Remove any unnecessary code or text.** For example, you should not include the template for training and scoring in your final submission.
- **Package your submission in a single file.** I will deduct points for multiple files or incorrect folder structure.
- **Name your notebooks correctly.** Include your name and Net-ID in the file name.
- **Train your TE/WOE encoders on the training set only.** You can train them on the full dataset for your final model.
- **Test your scoring function.** Most students scoring functions in the past din't work, so make sure to test yours before submitting your project.
- **Avoid common mistakes in your scoring function.** For example, your scoring function should not:
  - drop records, expect the target to be passed
  - fit TE/WOE/Scalers
  - return anything other than a Pandas DF.
- **Make sure you have the required number of engineered features.** 
- **Don't create features and then not use them in the model**, if there is a reason not to use the feature in the model, explain.
- **Don't include models in your notebook that you didn't train.** This is considered cheating and will result in a grade of zero for the project.
- **Consistently display model performance metrics.** Use AUC or AUCPR for all models and iterations, and don't switch between metrics. For sure don't use accuracy, it is misleading metric for the imbalanced datasets. 
- **Discuss your model results in a Markdown cell.** Don't just print the results; explain what they mean.
- **Include a conclusion section in your notebook.** This is your chance to summarize your findings and discuss the implications of your work.
- **Treat your notebook like a project report that will be read by your manager who can't read Python code.** Make sure your notebook is clear, concise, and easy to understand.
- **Display a preview of your dataset that you used for training.** This will help me understand what features you used in your model.
- **Use the libraries versions specified on eLearning.** For example, you should use H2O 3.42.0.2  
- **Use Python 3.10.11.** If you use another version and your code doesn't work on 3.10.11, it will be considered a bug in your code.
- **When running H2O and want to suppress long prints (for example model summary), include ";" at the end of the command.**
- **Don't include the dataset with your deliverables.** 
