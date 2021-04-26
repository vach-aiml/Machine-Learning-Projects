Hello everyone

This repository consists of standard projects related to Statistical Modelling, Supervised and Unsupervised Learning. These projects are provided with curated datasets from open-source ML repositories. These are well studied to achieve good insights of the data and are a perfect start to dive into Statistical Modeling and Machine Learning models.

**Project-1:  Statistical Learning - Project**

Leveraging customer information is paramount for most businesses. In the case of an insurance company, attributes of customers like the ones mentioned below can be crucial in making business decisions. Hence, knowing to explore and generate value out of such data can be an invaluable skill to have.

The data at hand contains medical costs of people characterized by certain attributes. We want to see if we can dive deep into this data to find some valuable insights using statistical inference and EDA techniques.

*Attribute Information:*

age : age of primary beneficiary                                                                                                                                                                                              

sex : insurance contractor gender, female, male

bmi : Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg / m ^ 2) using  the ratio of height to weight, ideally 18.5 to 24.9

children : Number of children covered by health insurance/Number of dependents

smoker : Smoking

region : the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.

charges : Individual medical costs billed by health insurance.

**Project-2: Supervised Learning_Project_Thera Bank**

Thera bank is interested in expanding Personal Loan Customer-base rapidly to bring in more loan business and in the process, earn more through the interest on loans. 

Various Supervised Learning Models are built and tested to help the Bank identify the potential customers who have higher probability of purchasing the loan. This will increase the success ratio while at the same time reduce the cost of the campaign.

Data of 5000 customers include customer demographic information (age, income, etc.), the customer's relationship with the bank (mortgage, securities account, etc.), and the customer response to the last personal loan campaign (Personal Loan).

_Attribute Information:_

ID: Customer ID	

Age: Customer's age in completed years

Experience: #years of professional experience

Income	Annual: Income of the customer ($000)

ZIPCode: Home Address ZIP code.

Family: Family size of the customer

CCAvg: Avg. spending on credit cards per month ($000)

Education: Education Level. 1: Undergrad; 2: Graduate; 3: Advanced/Professional

Mortgage: Value of house mortgage if any. ($000)

Personal Loan: Did this customer accept the personal loan offered in the last campaign?

Securities Account: Does the customer have a securities account with the bank?

CD Account: Does the customer have a certificate of deposit (CD) account with the bank?

Online: Does the customer use internet banking facilities?

CreditCard: Does the customer use a credit card issued by UniversalBank?


**Project-3: Supervised Learning_Project_Patient type_Classifier**

The problem statement is to classify the type of Patient from the biomechanical features of orthopedic patients.This is a binary classification problem with two classes 'Abnormal, 'Normal'. It is a simple dataset majorly used in understanding EDA pipeline and generate good insights of data. 

A KNN classifier is used and tuned for best performance.

_Attribute Information:_

Each patient is represented in the data set by six biomechanical attributes derived from the shape and orientation of the pelvis and lumbar spine (each one is a column):

pelvic incidence

pelvic tilt

lumbar lordosis angle

sacral slope

pelvic radius

grade of spondylolisthesis

class: 'Abnormal', 'Normal'


**Project-4: Unsupervised Learning_Project_PCA**

The purpose of the case study is to classify a given silhouette as one of three different types of vehicle, using a set of features extracted from the silhouette. Four "Corgie" model vehicles were used for the experiment: a double-decker bus, Chevrolet van, Saab 9000 and an Opel Manta 400 cars. This particular combination of vehicles was chosen with the expectation that the bus, van and either one of the cars would be readily distinguishable, but it would be more difficult to distinguish between the cars.

Using PCA from scikit learn and elbow plot to find out a reduced number of dimensions and Support vector machines with grid search to find out the best hyperparameters and cross-validation to find the accuracy.

_Attribute Information:_

NUMBER OF CLASSES

Total no. of datapoints= 946

No. in each class:

Opel 240

Saab 240

Bus  240

Van  226

NUMBER OF ATTRIBUTES = 18

