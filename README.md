# Forest-Cover-Type-Analysis-Phase-0

Dataset: [(https://www.kaggle.com/c/forest-cover-type-prediction)]


<ins>*Which data set have you chosen? What interested you about this problem?*</ins>

I chose the above dataset for the following reasons;

+ If successful, my model could be replicated to predict and track endangered plant species in the Amazon forest and other environmental initiatives .
+ Analyzing the right forest cover type is a major requirement for the forest management department to ensure ecological balance of the particular area. The traditional methods such as manual collection of samples in dense and wilderness areas like Amazon Forest can be fatal. Using the prediction model , one can avoid unnecessary fatality and reduce expense on collecting data from satellites by applying the forecast from the analyzed sample section.


<ins>*What columns in the data set are categorical and which are numerical?*</ins>
On the train.csv dataset the

+ Categorical columns:
1. ID
2. Hillshade_9am 3. Hillshade_Noon 4. Hillshade_3pm 5. Soil_Type
6. Cover_Type
7. Wilderness_Area

+ Numerical columns:
1. Elevation
2. Aspect
3. Slope
4. Horizontal_Distance_Hydrology
5. Vertical_Distance_Hydrology
6. Horizontal_Distance_Roadways
7. Horizontal_Distance_To_Fire_Points


<ins>*What is your target? What are the KPIs you plan on using to assess model performance in predicting this target?*</ins>

My target is to accurately predict the forest cover type using the other variables. 
I’ll use the MAPE (Mean Absolute Performance Error) and RMSE (Root Mean Squared Error) to gauge how accurately my model predicted the forest cover type. 


<ins>*The data set labeled "test" on Kaggle is not useful in this project -- why?*</ins>

The test dataset doesn’t contain the target column which is required  in observations calculations.


<ins>*What are the particular difficulties you see in this data set? What unique challenges might you encounter in analyzing it?*</ins>

1. The dataset is very large, i.e. the soil type column has 40 variables making it harder to find the best model to use. Additionally, the dataset has 7 targets i.e. the different forest cover types therefore making predicting is a bit more tedious. 
2. Scientific terminologies such as azimuth, hillshade and hydrology can be difficult for novice data analysts or non-technical staff to understand.
3. Lastly, the dataset is 7 years old and with the drastic climate changes over the last years, my model might not predict forest type cover accurately. 
