# Machine Learning

## Arthur Samuel(1959) describes machine learning as a field of study that gives computers ability to learn without being explicitly programmed.
## Tom Mitchell(1997) gives more modern definition, "Computer program is said to learn from experience E with respect to some class of tasks T and some performance measure P, If its performance in task T as measure by P, improves with experience E."

* #### Example: Playing Checker
    #### E Experience of playing many games of checkers.
    #### T Task of playing checker.
    #### P The probability of the algorithm will win the next game.

## In general, Any machine learning problem can be assign to one of the two broad classifications:
* ## Supervised Learning
* ## Unsupervised Learning 

# Supervised Learning
## Supervised learning is machine learning task of learning a function that maps input to an output value based on training dataset.
## Training dataset is a collection of training examples, Each example is a pair consisting of input object(Typically vector) and desired output object(Called "Supervisory Signal")
## Based on training dataset SL algorithm infers a function, having idea that there is relationship between the input and the output.

## Supervised Learning problems are categorized into "Regrassion" and "Classification" Problems.
* ### Regression algorithm tries to predict results within the continuous output, meaning algorithm tries to map input variables to continuous function.
    * #### Regression problem example is trying to predict age of person based on thier image.
* ### Classification algorithm tries to predict results into discrete output, in other words algorithm tries to map input variables to an discrete set of categories.
    * #### Classification problem example is trying to predict given information about person's tumor whether it is malignant or benign.
