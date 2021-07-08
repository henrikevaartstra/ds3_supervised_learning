# Repository for Data Science 3 - Supervised Learning (july 2021)
Henrike Vaartstra 352664

h.f.j.j.vaartstra@st.hanze.nl

## The data
### Predicting poisonous mushrooms using physical appearance of mushrooms
The data used in this assignment is the 'Mushrooms' data set from archive.ics.uci.edu. The set can be found here https://archive.ics.uci.edu/ml/datasets/mushroom. The main purpose of this dataset is classifying poisonous and edible mushrooms on the basis of physical appearances.

This data set includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family. Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended. This latter class was combined with the poisonous one. The Guide clearly states that there is no simple rule for determining the edibility of a mushroom; no rule like ''leaflets three, let it be'' for Poisonous Oak and Ivy.

The data consists of:
- agaricus-lepiota.data: the observations itself
- agaricus-lepiota.names: the description of the observations

The purpose of this assignment is to see if I can classify poisonous mushrooms.

## Readme
The data can be found in the folder 'data'. In this folder there are two files, which are both read in in the jupyter notebook.
The first file ending with '.names' contains the descriptions of the observations and the file ending with '.data' contains the actual observations themselves.

The folder 'run-images' contains the images that I have run while creating this notebook. I decided to already place them into a seperate file because, as I also indicate in the notebook, running/plotting the learning curves takes some time (therefor they are commented out at default) and thus you do not have to run them and can already find them in this folder.

#### To run the notebook:
1. Clone this repository
2. Run the file '352664_supervised_learning_DS3_final.ipynb'
3. The neede packages can be found in the list below

#### Requirements
- Python 3.8 or up
- Matplotlib
- Seaborn
- Numpy
- Pandas
- sklearn
