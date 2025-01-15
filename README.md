This is a series of notebooks used in the paper "Automatic large-scale political bias detection of news outlets" By Rönnback, Emmery and Brighton. Note that the necessary data is openly available, but not provided here. For the data, please consult :
- GDELT: https://blog.gdeltproject.org/gdelt-2-0-our-global-world-in-realtime/
- Media Bias Fact Check labels: https://mediabiasfactcheck.com/mbfcs-data-api/
- Robertson et al's labels: https://personalization.ccs.neu.edu/Projects/Partisanship/

We do however provide the aggregate data used to train, validate and test the models, as well as the best performing model's predictions on all of the data (pytorch_predictions.csv).

Note that file paths need to be modified in the code to fit your download locations.

The best-performing model is provided. The architecture can be found in the file 0X_Pytorch Model - categorical data included.ipynb.
We also provide the best SVC model which is used for SHAP analysis.


