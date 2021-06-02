- 👋 Hi, I’m Harshal Garg  
- 🏢 I'm a working professional as an IT Professional in Infosys, India  
- 👀 I’m interested in Data Science, Machine Learning and Deep Learning  
- 📫 You can contact me via  
  - 📞 Phone - +91-9977816300  
  - 📧 [Email](mailto:harshalgargwork@gmail.com)  
  - [Linkedin](https://linkedin.com/in/harshalgarg)  
- 🖊 My ML blogs on [Medium](https://harshalgarg.medium.com/)

---

[Here](https://github.com/gargharshal/gargharshal/kaggle) are all my Machine learning projects.  

**Dog Breed Identification – CNN**

[Project Link GitHub](https://github.com/gargharshal/Kaggle/blob/master/Dog%20Breed%20Indentification/Dog%20Breed%20Identification%20-%20My%20Version.ipynb) - If this doesn't render, use this link [Jupyter nbviewer](https://nbviewer.jupyter.org/github/gargharshal/Kaggle/blob/master/Dog%20Breed%20Indentification/Dog%20Breed%20Identification%20-%20My%20Version.ipynb) (view only)

- Used [Kaggle dataset](https://www.kaggle.com/c/bluebook-for-bulldozers) to create a dog breed identifier based on a single image given by the user image.
- I used **Transfer Learning** by using a **pretrained Keras model**.
- I trained every model on a small dataset to find the best chosen based on **accuracy** and
**parameter count**.
- I created **callbacks** to **create logs** and to prevent the model from
**overfitting**.
- The final model **NASNetMobile** was trained on the full dataset and saved as a ‘.h5’ file which was used to make **predictions.**

<!-- * [Dog Breed Identification - Course Version](https://github.com/gargharshal/Kaggle/blob/master/Dog%20Breed%20Indentification/Dog%20Breed%20Identification%20-%20Course%20Version.ipynb) Project created from a course referred, [Original Link](https://github.com/mrdbourke/zero-to-mastery-ml/blob/master/section-3-structured-data-projects/end-to-end-bluebook-bulldozer-price-regression.ipynb) of tutor's version -->

**Bulldozer Price Prediction - Random Forest Regression**

[Project Link GitHub](https://github.com/gargharshal/Kaggle/blob/master/Bluebook%20for%20Bulldozer/Blue%20Book%20for%20Bulldozers.ipynb) - If this doesn't render, use this link [Jupyter nbviewer](https://nbviewer.jupyter.org/github/gargharshal/Kaggle/blob/master/Bluebook%20for%20Bulldozer/Blue%20Book%20for%20Bulldozers.ipynb) (view only)

- Used [Kaggle dataset](https://www.kaggle.com/c/bluebook-for-bulldozers) to create a model predict bulldozer price.
- Given the data of previous sales prices of bulldozers, we are trying
to predict the sales price of the bulldozers which have similar
characteristics.
- The data was first analyzed to find **missing values** and the **most
important features.**
- Missing values were filled, and the data was made compatible for
modelling.
- **RandomForestRegressor** was chosen based on [Sklearn Algorithm
Cheat Sheet](https://scikit-learn.org/stable/tutorial/machine_learning_map/index.html)
- After hyperparameter tuning, the model was trained and tested.

**Heart Disease - Logistic Regression**

[Project Link GitHub](https://github.com/gargharshal/Kaggle/blob/master/Heart%20Disease/Heart%20Disease.ipynb) - If this doesn't render, use this link [Jupyter nbviewer](https://nbviewer.jupyter.org/github/gargharshal/Kaggle/blob/master/Heart%20Disease/Heart%20Disease.ipynb) (view only)

- Used [Kaggle Dataset](https://www.kaggle.com/ronitf/heart-disease-uci) to predict if a person has heart disease or not.
- The data on Multiple models to find the best one based on **precision**, **recall**, **f1-score**
- Understanding the parameters involved and their importance using **histograms**, **scatter plots**,  **Confusion Matrix**.
- Using **Logistic Regrssion** as the final model, fine tunning hyper parameters with **RandomizedSearchCV** and then training the best model.
- Understanding the model performance using roc curve, classification_report, etc.

**Titanic - Random Forest Classifier**
[Project link GitHub](https://github.com/gargharshal/Kaggle/blob/master/Titanic/Titanic%20prediction.ipynb) - If this doesn't render, use this link [Jupyter nbviewer](https://nbviewer.jupyter.org/github/gargharshal/Kaggle/blob/master/Titanic/Titanic%20prediction.ipynb) (view only)

- Used [Kaggle Dataset](https://www.kaggle.com/c/titanic) build a **predictive model** that answers the question: “what sorts of people were more likely to survive the titanic ship wrecks?”
- Understanding the **parameters** and **dataset**
- Filling the missing values **mean or median**
- Transforming the data using **OneHotEncoder** to feed into the **classifier**.
- Training multiple models with test data to find the best one and creating predictions using **LogisticRegression**.



<!---
gargharshal/gargharshal is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
