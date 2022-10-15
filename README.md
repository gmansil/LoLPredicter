# LoLPredicter
Binary Classification model which predicts which team will win based on rolling averages of the 2022 Spring and Summer seasons.

## Description
LolPredicter is a Deep Learning Binary Classification model which is able to predict a winning team based on rolling averages. The model is trained on a dataset of the North American, European, Korean, and Chinese professional e-sport leagues. In order to allow for variables to initially carry equal weights, I used sklearns MinMaxScaler. Variables which could not be numerically defined were one hot enconded such as each team's bans. After training and testing the model, the dataset is merged based on matches rather then individual teams in order to better visualize if the model predicted accurately.

## Dependencies
The required libraries and dependencies are listed at in the file. 

## Execution
To use the program with any League of Legends e-sports dataset, the only conditions to look for are whether the variables being altered match and that the data sets record the same info. This model can be expanded or minimilized depending on what regions or lack of the dataset contains.
