# Building_Energy_Prediction
How much energy will a building consume?

## Business Objective:
Under pay-for-performance financing, the building owner makes payments based on the difference between their real energy consumption(with retrofits) and what they would have used without any retrofits. The latter values have to come from a model. With better estimates of how much the energy a building is actually going to consume, large scale investors and financial institutions will be more inclined to invest in this area to enable progress in building efficiencies. Hence, significant investments can be made to improve building efficiencies to reduce costs and emissions.

Retrofits:- Energy saving instruments

### Data Source:
ASHRAE(Kaggle)

### Data Size and Information:
#### Training Data: 
Energy consumption of 1,450 buildings for 4 meter types for 2016 year on an hourly basis.
Data size: 20216100 rows * 4 columns

#### Weather Data:
Weather data for 16 sites from 2016 to 2018 on an hourly basis.
Data size: 417016 rows * 9 columns

#### Building Information Data:
Information of 1450 buildings about their construction year, # of floors etc.
Data size: 1449 rows * 6 columns

#### Testing Data:
Testing will be done for 1450 buildings for their energy consumption from 2017 to 2018 year.
Data size: 41697600 rows * 4 columns

### Evaluation Metric:
Predictions will be tested on Root Mean Square Logarithmic Error(RMSLE). 




