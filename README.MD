### Kaggle-titanic


### Dependancies:
See environment.yml for the complete dependency list.

### Environment:
You can create a conda environment with all required dependencies by running conda env create in the root of the repository. Install the environment with:

conda env create -f environment.yml


### Kaggle Competition | Titanic Machine Learning from Disaster
>The sinking of the Titanic is one of the most infamous shipwrecks in history.
>On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.
>While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.
>In this challenge, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

From the competition (https://www.kaggle.com/c/titanic).

### Goal for this Notebook:s
* feature creation
* sklearn pipelines
* target encoding
* XGBoost, Random Forest
* Cross-validation
* Performance metrics: accuracy, precision/recall, ROC
* Stacking
* Hyperparameter searching/tuning