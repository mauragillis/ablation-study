# ISIC 2024 Challenge Ablation Studies 

## Overview 

The 'ISIC 2024 – Skin Cancer Detection with 3D-TBP’ was hosted on Kaggle from June 2024 until September 2024. A description of the first place winner's solution may be found [here](https://www.kaggle.com/competitions/isic-2024-challenge/discussion/533196).

We categorized model features into the following categories: basic metadata (ex. age, sex, etc.), tiles (raw images), WB360 features, and patient contextual (calculated using all lesions of a patient).

We performed nine ablation experiments in order to test the significance of each of these features on the winning model. Each experiment with a description can be found in this repository.


## Instructions

1. Create a free [Kaggle account](https://www.kaggle.com/account/login)
2. Access the starter environment [here](https://www.kaggle.com/code/mauragillis19046/ablation-study-starter-environment). Select the three dots in the right hand corner, and click "Copy and Edit".
3. Select File -> Import Notebook -> GitHub and search for this repository
4. Import the notebook you wish to run. On the right side toolbar, click "Submit" to have the notebook scored with the 'ISIC 2024 – Skin Cancer Detection with 3D-TBP’ metrics.
5. Wait until the notbook finishes running. It may take up to tweleve hours for experiments where tiles were used.
6. To view your score, go to the [challenge web page](https://www.kaggle.com/competitions/isic-2024-challenge/submissions) and then click "Submissions".
