# weka_job_classification

SMO - configuration file for the SMO classification method in Weka. When selecting settings for the SMO classifier, use "load" to import these settings.

SMO_classification.model - model produced from running the SMO classifier. Load into the Weka classification tool in order to see the results yielded.

StringToWordVector - configuration file for the StringToWordVector filter in Weka. When selecting settings for the StringToWordVector filter, use "load" to import these settings.

all_prediction_set.csv - prediction output from the SMO classification model.

cs_prediction-sec.csv - prediction output from the SMO classification model. Filtered to only contain rows classified as CS related. Joined with the Job Posting file.

trainingset.xlsx - a table of indices for the job postings selected for manual classification along with their designated classifications.

job_posting.csv - a file containing the word vectors for each job posting. Due to the file size exceeding github's maximum, this file is unable to be shared here on github. This file can be downloaded from Google Drive at the following link: https://drive.google.com/file/d/0B4N9rQzcyd3MRWlyVUVCdUZ0TlU/view?usp=sharing
