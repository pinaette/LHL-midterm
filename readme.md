# Flight delay prediction for LHL midterm

This repository contains the notebooks and supporting files for the Lighthouse Labs midterm, group project by [**Jay Tam**](https://github.com/jtam08) and [**Pinar Orbay**](https://github.com/pinaette).

### List of included files:

- Raw flights data, sampling every 300th entry from the database (*flights_raw.txt*).
- Notebook containing some of our EDA work (*0-data_exploration.ipynb*).
- Notebook for creating a "working file" from the raw data (*1-data_preprocessing.ipynb*).
- Working file with features stripped and scaled (*full_scaled_data.csv*).
- Notebook for trying different models on the working file (*2-model_selection.ipynb*).
- Notebook for hyperparameter tuning on selected models (*3-parameter_tuning.ipynb*).
- Testing data for the project: flights from the first week of January 2020 (*test-jan-1_7.csv*).
- Notebook for training the final model and making predictions on testing data (*4-final.ipynb*).
- Final predictions file (*submission.csv*).