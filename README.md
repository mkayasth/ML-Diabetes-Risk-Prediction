# Machine-Learning---Diabetes-Risk-Prediction

1) Introduction and Data Source

Diabetes is a chronic health condition that occurs when the blood glucose is too high. According to the CDC, diabetes is the 8th leading cause of death in the United States, and 1 in 5 of the adults with diabetes in the US do not even know that they have it. If unmanaged, diabetes can lead to various complications including heart disease and stroke, neuropathy, compromised immune system, and kidney damage.

Our dataset comes from Kaggle (https://www.kaggle.com/datasets/prosperchuks/health-dataset/data), compiled from the Behavioral Risk Factor Surveillance System (BRFSS) 2015. BRFSS is a collaborative project between all the states in the United States and the Centers for Disease Control and Prevention (CDC) designed to measure behavioral risk factors for the adult population (aged 18 years of age and older) residing in the United States. Our dataset is a collection of 70,692 survey responses with 17 feature variables and 1 target variable.

The features of our dataset are as follows:
Age: 13 different age categories starting from (1=18-24 yrs, 2=25-29 yrs, 3=30-34 yrs, 4=35-39 yrs, 5=40-44 yrs, 6=45-49 yrs, 7=50-54 yrs, 8=55-59 yrs, 9=60-64 yrs, 10=65-69 yrs, 11=70-74 yrs, 12=75-79 yrs, 13 = 80 or older).
Sex: 0 for male, 1 for female.
HighChol: 0 for no high cholesterol, 1 for high cholesterol.
CholCheck: 0 for no cholesterol check in 5 yrs, 1 for yes.
BMI
Smoker: 0 for not smoked 5 packs of cigarettes in lifetime, 1 for yes.
HeartDiseaseorAttack: 0 for no, 1 for yes.
PhysActivity: in the past 30 days, 0 for no and 1 for yes.
Fruits: 1 for fruit consumed 1 or more times daily, 0 for no.
Veggies: 1 for vegetables consumed 1 or more times daily, 0 for no.
HvyAlcoholConsump: 0 for no, 1 for yes.
GenHlth: 1 =excellent, 2=very good, 3=good, 4=fair, 5=poor.
MentHlth:1-30 (days of poor mental health in a month).
PhysHlth: 1-30
DiffWalk: serious difficulty while walking or climbing stairs (0 for no, 1 for yes).
Stroke: 0 for no, 1 for yes.
HighBP: 0 for no, 1 for yes.
Diabetes: 0 for no, 1 for yes.




** Research Questions **

a) How do the factors interact with each other in influencing the likelihood of these health conditions?
b) Can we develop a predictive model that accurately identifies individuals at risk of these conditions?
c) What is the impact of lifestyle factors (like smoking, alcohol consumption, physical activity) on the likelihood of these health conditions?
d) Are there significant differences in the prevalence of these health conditions across different demographic groups (like age, and gender)?
