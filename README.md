# hypothyroidism-detection
![image](https://user-images.githubusercontent.com/97290284/190846856-ec4633c3-59ef-4d85-9cb5-1eb3a38a8ae8.png)


The objective of the project is to predict whether a patient has thyroid disease or not based on their medical data including results of some tests, and find the major factors that may lead to signs of presence of thyroid, using machine learning models and statistical analysis.

The data being used has been taken from UCI Machine Learning Repository (https://archive.ics.uci.edu/ml/datasets/thyroid+disease). The dataset used for analysis is called hypothyroid. The data contains 28 explanatory variables that contain a lot of information about the patient’s medical history, relevant information about patients such as tests that have been done and their results etc.
The explanatory variables contain quantitative as well as qualitative data. The qualitative data has been converted into categorical data in order to use them in machine learning models.
The target variable i.e. binaryClass has two possible values P and N, where P indicates that the patient does not have thyroid disease i.e. their thyroid gland is working properly, while N signifies the opposite. The aim of the project is to create a model to accurately predict the presence of thyroid disease in a patient.

The presence of a thyroid is the target (or dependent) variable and all other variables are considered the explanatory (or independent) variables. 
The explanatory variables have been used to make predictions for presence of thyroid in a person. These variables were considered to be independent and binary class, the dependent variable, is predicted based on theses dependent variables. The explanatory variables are either numeric such as age, FTI, T4U etc. or Booleans such as sex, on thyroxine, FTI_measured etc.
The explanatory variables are:
1.	Age: age of the patient
2.	Sex: sex of the patient, m: male and f: female
3.	On thyroxine: whether a person is on thyroxine or not
4.	Query on thyroxine: a person has a query about thyroxine
5.	On antithyroid medicine: whether a person is on antithyroid medication
6.	Sick: whether the person under study is sick
7.	Pregnant: whether the person under study is pregnant
8.	Thyroid surgery: whether the person under study has undergone thyroid surgery
9.	I131 treatment: whether a person has undergone I131 treatment, in which the aim of treatment is to treat hyperthyroidism by destroying sufficient thyroid tissue to render the patient either euthyroid or hypothyroid.
10.	Query hyperthyroid: whether patient believes they have hyperthyroid
11.	Query hypothyroid: whether patient believes they have hypothyroid
12.	Lithium: whether a patient has undergone lithium treatment that is used to treat severe hyperthyroid
13.	Goitre: whether a patient has goitre
14.	Tumor: whether a patient has tumour
15.	Hypopituitary: whether a patient has hypopituitarism i.e. when you have short supply of one or more of the pituitary glands
16.	Psych: whether a patient has psychiatric signs such as forgetfulness, fatigue, mental slowness etc.
17.	TSH_measured: whether TSH was measured or not
18.	TSH: TSH level in blood from blood tests
19.	T3_measured: whether T3 was measured or not
20.	T3: T3 level in blood from blood tests
21.	TT4_measured: whether TT4 was measured or not
22.	TT4: TT4 level in blood from blood tests
23.	T4U_measured: whether T4U was measured or not 
24.	T4U: T4U level in blood from blood tests
25.	FTI_measured: whether FTI was measured or not 
26.	FTI: FTI level in blood from blood tests
27.	TBG_measured: whether TBG was measured or not
28.	TBG: TBG level in blood from blood tests

The target variable, binaryClass i.e. the presence of thyroid disease, has 3481 P’s and 291 N’s, i.e. in the data there are 3481 people who do not have thyroid while 291 people have thyroid.

After analysis, the following features were found to have the most impact on our target variable: <br />
  TSH, FTI, TT4, T3, age

The following accuracy scores were obtained by the models:
  Logistic Regression : 0.9536423841059603 <br />
  Support Vector Machines (with linear kernel) : 0.9615894039735099 <br />
  Decision Tree : 0.9788079470198675 <br />

