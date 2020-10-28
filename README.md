# Forest Fire Detection

<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab">

```python
Hello World ! 

from AI import ForestFirePredictions
```

Welcome to the Hacktoberfest Challenge for Artificial Intelligence | Machine Learning !

Today we will be assessing your skills to Predict Forest Fire Areas given its various parameters!

## Features Provided
For this dataset you are provided with the following features/attributes of a park:

X - x-axis spatial coordinate within the park

Y - y-axis spatial coordinate within the park

month - month of the year: "jan" to "dec"

day - day of the week: "mon" to "sun"

FFMC - FFMC index from the FWI system: 18.7 to 96.20 : The Fine Fuel Moisture Code (FFMC) represents fuel moisture of forest litter fuels under the shade of a forest canopy. It is intended to represent moisture conditions for shaded litter fuels, the equivalent of 16-hour timelag. It ranges from 0-101. Subtracting the FFMC value from 100 can provide an estimate for the equivalent (approximately 10h) fuel moisture content, most accurate when FFMC values are roughly above 80.

DMC - DMC index from the FWI system: 1.1 to 291.3 : The Duff Moisture Code (DMC) represents fuel moisture of decomposed organic material underneath the litter. System designers suggest that it is represents moisture conditions for the equivalent of 15-day (or 360 hr) timelag fuels. It is unitless and open ended. It may provide insight to live fuel moisture stress.


DC - DC index from the FWI system: 7.9 to 860.6 : The Drought Code (DC), much like the Keetch-Byrum Drought Index, represents drying deep into the soil. It approximates moisture conditions for the equivalent of 53-day (1272 hour) timelag fuels. It is unitless, with a maximum value of 1000. Extreme drought conditions have produced DC values near 800.

ISI - ISI index from the FWI system: 0.0 to 56.10 : The Initial Spread Index (ISI) is a numeric rating of the expected rate of fire spread. It is based on wind speed and FFMC. Like the rest of the FWI system components, ISI does not take fuel type into account. Actual spread rates vary between fuel types at the same ISI.

temp - temperature in Celsius degrees: 2.2 to 33.30

RH - relative humidity in %: 15.0 to 100

wind - wind speed in km/h: 0.40 to 9.40

rain - outside rain in mm/m2 : 0.0 to 6.4

area - the burned area of the forest (in hectares): 0.00 to 1090.84 (this output variable is very skewed towards 0.0, thus it may make sense to model with the logarithm transform).

More Technical Data about the features could be found out at [Fire Weather Index System](https://www.nwcg.gov/publications/pms437/cffdrs/fire-weather-index-system) & [FWI Canada](https://cwfis.cfs.nrcan.gc.ca/background/summary/fwi).

## Submission Criteria
Anybody part of the Developer Students Club Community is eligible to contribute to this Open Source Project.

## Submission Procedure

1. Fork this repository.
2. Open this [Google Colaboratory Notebook](https://www.nwcg.gov/publications/pms437/cffdrs/fire-weather-index-system), & copy it to your google drive(**recommended**) or alternatively, use the provided Sample_Submission.ipynb Jupyter Notebook inside the template folder if you want to modify the submission locally on your machine. Create yur own model and fill in the missing blanks in the functions provided there.
3. When you are finished updating the functions, convert your Notebook into a Python Script as you have to upload both of these under the submissions folder. 
4. Add your files inside the submissions folder on your github repository. Make sure to include the both the .py and the .ipynb files in the following format : Accuracy(rounded off to two digits)_YourClassifierName_YourProjectName_YourTeamName/YourName, {For example : 68.23_DecisionTreeClassifier_DTFire_DeadlyDuo}. If needed you can also create a requirements file containing all dependencies/modules with versions in the requirements directory under submissions with the same name format as above.
5. Send us a Pull Request and we will perform some preliminary checks, before finally Merging your Contents.

## Code of Conduct
Copying Code from other repos will lead to immediate disqualification.


## Credits
The credits for this repository is hidden and will be provided post event completion/evaluation.
