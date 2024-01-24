# Flood Damage Prediction
## Data
Download the raw data here: https://zenodo.org/records/4355693. Use the USFD file (USFD_v1.0.csv).

## How to use this code

### Preprocessing
Use Preprocessing.ipynb to preprocess. This will clean the dataset to remove irrelavant attributes, impute or remove incomplete data, and discretize attributes.
Change this line, in first block, to update the location of the file:
~~~
# Load in dataset as a pandas dataframe
flood_data_raw = pd.read_csv("drive/My Drive/USFD_v1.0.csv")
~~~

### Data visualization
Use DataVisualization.ipynb to generate graphs that describe and analyze the preprocessed data. A bar graph will be generated to show the frequencies of different damage values. This code will also create a correlation matrix, which shows the correlation between any two attributes. 

### Models
The models folder contains classification and regression models to generate predictions for flood damage.

### To learn more about results visit the paper
