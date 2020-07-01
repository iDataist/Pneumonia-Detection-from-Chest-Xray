# Pneumonia Detection from Chest Xray

## Project Overview

Chest X-ray exams are one of the most frequent and cost-effective types of medical imaging examinations. Deriving clinical diagnoses from chest X-rays can be challenging, however, even by skilled radiologists. When it comes to pneumonia, chest X-rays are the best available method for point-of-care diagnosis. More than 1 million adults are hospitalized with pneumonia and around 50,000 die from the disease every year in the US alone. The high prevalence of pneumonia makes it a good candidate for the development of a deep learning application for two reasons: 1) Data availability in a high enough quantity for training deep learning models for image classification 2) Opportunity for clinical aid by providing higher accuracy image reads of a difficult-to-diagnose disease and/or reduce clinical burnout by performing automated reads of very common scans.

I analyzed data from the NIH Chest X-ray Dataset and trained a CNN to classify a given chest x-ray for the presence or absence of pneumonia. First, I curated training and testing sets that were appropriate for the clinical question at hand from a large collection of medical images. Then, I created a pipeline to extract images from DICOM files that could be fed into the CNN for model training. Lastly, I wrote an FDA 501(k) validation plan that formally describes the model, the data that it was trained on, and a validation plan that meets FDA criteria in order to obtain clearance of the software being used as a medical device.

The NIH Chest X-ray Dataset includes 112,000 chest x-rays acquired from 30,000 patients with clinical labels for each image that were extracted from their accompanying radiology reports.

## Key Skills Demonstrated

- 2D medical imaging data analysis and preparation of a medical imaging model for regulatory approval
- Recommend appropriate imaging modalities for common clinical applications of 2D medical imaging
- Perform exploratory data analysis (EDA) on medical imaging data to inform model training and explain model performance
- Establish the appropriate ‘ground truth’ methodologies for training algorithms to label medical images
- Extract images from a DICOM dataset
- Train common CNN architectures to classify 2D medical images
- Translate outputs of medical imaging models for use by a clinician
- Plan necessary validations to prepare a medical imaging model for regulatory approval

## Project Steps

- Exploratory Data Analysis
- Building and Training the Model
- Clinical Workflow Integration
- FDA Preparation
