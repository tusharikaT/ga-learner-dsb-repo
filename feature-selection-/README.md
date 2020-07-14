The problem statement revolves around the need to predict the forest cover type (the predominant kind of tree cover) from strictly cartographic variables (as opposed to remotely sensed data).

It includes four wilderness areas located in the Roosevelt National Forest of northern Colorado. These areas represent forests with minimal human-caused disturbances, so that existing forest cover types are more a result of ecological processes rather than forest management practices.

The study area includes four wilderness areas located in the Roosevelt National Forest of northern Colorado. Each observation is a 30m x 30m patch. You are asked to predict an integer classification for the forest cover type. The seven types are:

1 - Spruce/Fir 2 - Lodgepole Pine 3 - Ponderosa Pine 4 - Cottonwood/Willow 5 - Aspen 6 - Douglas-fir 7 - Krummholz

about data set :
You can observe there are more than 20+ features in the dataset. We will be working with this dataset to gather insights and look at the feature importance of each feature contributing towards the target variable. The data is in raw form (not scaled) and contains binary columns of data for qualitative independent variables such as wilderness areas and soil type.
Feature	Description
Elevation	Elevation in meters
Aspect	Aspect in degrees azimuth
Slope	Slope in degrees
Horizontal Distance To Hydrology	Horz Dist to nearest surface water features
Vertical Distance To Hydrology	Vert Dist to nearest surface water features
Horizontal Distance To Roadways	Horz Dist to nearest roadway
Hillshade_9am (0 to 255 index)	Hillshade index at 9am, summer solstice
Hillshade_Noon (0 to 255 index)	Hillshade index at noon, summer solstice
Hillshade_3pm (0 to 255 index)	Hillshade index at 3pm, summer solstice
Horizontal Distance To Fire Points	Horizontal Dist to nearest wildfire ignition points
Wilderness_Area (4 binary columns, 0 = absence or 1 = presence)	Wilderness area designation
Soil_Type (40 binary columns, 0 = absence or 1 = presence)	Soil Type designation
Cover_Type (7 types, integers 1 to 7)	Forest Cover Type designation


Outcomes :
How are the features important to our model.
How to select the most significant features out of many.
How to perform univariate feature selection.
How to perform a multivariate feature selection.
