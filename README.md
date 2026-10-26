# Practical Machine Learning: Course Project

Predicting how well people perform barbell lifts (the `classe` variable) from accelerometer data on the belt, forearm, arm and dumbbell.

- **Analysis (R Markdown):** `index.Rmd`
- **Compiled report:** `index.html` (viewable online via GitHub Pages)

The final model is a random forest with 5-fold cross validation. It reached 99.4% accuracy on a held-out validation set, for an expected out-of-sample error of about 0.6%.

Data: Velloso, E.; Bulling, A.; Gellersen, H.; Ugulino, W.; Fuks, H. *Qualitative Activity Recognition of Weight Lifting Exercises.* Proceedings of the 4th Augmented Human International Conference, 2013. http://groupware.les.inf.puc-rio.br/har
