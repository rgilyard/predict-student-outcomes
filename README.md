# predict-student-outcomes
Predict student outcomes in Virtual Learning Environments using a Cluster-Then-Predict approach with Gaussian Process Classification

## OULAD_database_creation.ipynb
`OULAD_database_creation.ipynb` takes the provided CSV files from the anonymized dataset and converts them into a .db file. This .db file serves as a SQLite database for subsequent data exploration and analysis.

## OULAD_exploration.ipynb
`OULAD_exploration.ipynb` serves as an initial step into data exploration. It browses through the tables in the SQLite database and generates a small, preliminary subset of the dataset for initial analysis.

## prelim_gaussian_process_model.ipynb
`prelim_gaussian_process_model.ipynb` employs a Gaussian Process model to analyze the preliminary dataset. It serves as an initial effort to understand the data's behavior under Gaussian Process modeling.

## prelim_extratrees.ipynb
`prelim_extratrees.ipynb` applies an Extra Trees model to the preliminary dataset. This notebook serves to evaluate how well Extra Trees can perform with the given data.

## prelim_rotation_forest.ipynb
`prelim_rotation_forest.ipynb` utilizes a Rotation Forest model to classify the preliminary dataset. This aims to assess the Rotation Forest's performance and suitability for the problem at hand.
