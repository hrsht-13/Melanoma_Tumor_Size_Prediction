# Melanoma_Tumor_Size_Prediction
Melanomas present in many different shapes, sizes, and colors. That’s why it’s tricky to provide a comprehensive set of warning signs. Melanoma, also known as malignant melanoma, is a type of skin cancer that develops from the pigment-producing cells known as melanocytes. The primary cause of melanoma is ultraviolet light (UV) exposure in those with low levels of the skin pigment melanin. The UV light may be from the sun or other sources, such as tanning devices. 
Melanoma is the most dangerous type of skin cancer. Globally, in 2012, it newly occurred in 232,000 people. In 2015, there were 3.1 million people with active disease, which resulted in 59,800 deaths. Australia and New Zealand have the highest rates of melanoma in the world. There are also high rates in Northern Europe and North America, while it is less common in Asia, Africa, and Latin America. In the United States melanoma occurs about 1.6 times more often in men than women.
## Challenge
To predict the melanoma tumor size based on various attributes. 
## Dataset
1. Train.csv - 9146 rows x 9 columns
2. Test.csv - 36584 rows x 8 columns
3. Sample Submission - Acceptable submission format
 
Attributes Description:

1. mass_npea:  the mass of the area understudy for melanoma tumor
2. size_npear: the size of the area understudy for melanoma tumor
3. malign_ratio: ration of normal to malign surface understudy
4. damage_size: unrecoverable area of skin damaged by the tumor
5. exposed_area: total area exposed to the tumor
6. std_dev_malign: standard deviation of malign skin measurements
7. err_malign: error in malign skin measurements
8. malign_penalty: penalty applied due to measurement error in the lab
9. damage_ratio: the ratio of damage to total spread on the skin
10. tumor_size: size of melanoma_tumor

## Evaluation Criteria
The submission will be evaluated using the RMSE metric. One can use ```np.sqrt(sklearn.mean_squared_error(actual, predicted))```

## LeaderBoard
No. of registered: 305
###### Link: https://www.machinehack.com/hackathons/melanoma_tumor_size_prediction_weekend_hackathon_15

 
