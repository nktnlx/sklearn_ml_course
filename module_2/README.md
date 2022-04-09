# Module 2 -- Selecting the best model

## Wrap-up
* **Overfitting** is caused by the **limited size of the training set**, the **noise** in the data, and the **high flexibility** of common machine learning models.

* **Underfitting** happens when the learnt prediction functions suffer from **systematic errors**. This can be caused by a choice of model family and parameters, which leads to a **lack of flexibility** to capture the repeatable structure of the true data generating process.

* For a fixed training set, the objective is **to minimize the test error** by adjusting the model family and its parameters to **find the best trade-off between overfitting for underfitting**.

* For a given choice of model family and parameters, **increasing the training set size will decrease overfitting** but **can also cause an increase of underfitting**.

* The **test error of a model** that is neither overfitting nor underfitting can still be high if the variations of the target variable cannot be fully determined by the input features. This **irreducible error is caused by what we sometimes call label noise**. In practice, this often happens when we do not have access to important features for one reason or another.