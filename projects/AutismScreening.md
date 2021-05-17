---
title: Screening for Autism in Adults
description: Using machine learning methods to quickly predict if an individual is likely to have autism
---

## Problem Statement
Autism is characterized primarily by social and behavioral challenges, including: differences in how people perceive their environments and those around them, communication barriers due to how people both process and verbalize information, and the need to maintain rigid patterns and rituals that can interfere with quality of life.  Autism is most often diagnosed in toddlers, but some individuals on the autism spectrum disorder (ASD) are classified as “high-functioning” and can go undiagnosed into adulthood. There are currently no standard diagnostic criteria for adults with suspected ASD, but they are in development (as of 2018). Waiting times for an adult to receive an autism diagnosis are lengthy and procedures are not cost effective, often requiring multiple visits and interactions with clinicians . A short and effective diagnostic screening tool is needed to reduce the burden of cost and time of adults who are undiagnosed with ASD.

## Proposal
Using the Adult Autism Screening dataset, I will create a random forest model that will evaluate various features within the data to predict if an individual has autism. This is a supervised learning problem, with the target variable of Class/ASD having two levels: YES and NO. Since the dataset already contains the true values of the target variable, I will be splitting the data into a test set and a train set. I will use recall, precision, and f1 score as the metrics to judge the efficacy of my models.

Also, I plan to use the area under the ROC curve to determine the appropriate threshold for the classifier. My aim in doing this is to reduce the false positive rate of the model. A false diagnosis for autism could result in unnecessary and costly follow-up for the individual, as well as the use of resources for someone who does not require them.

The model will then be able to provide a quick screening tool that can be used to determine whether a person may have autism and should seek guidance on its management. This will reduce the effort needed to diagnosis adults with ASD and allow for quick treatment options for the patients. 


## Relevant Links
* [Whitepaper Documentation](https://github.com/tripleee19/Autism-Screening-in-Adults/blob/main/Screening%20Tool%20for%20Autism%20in%20Adults.docx)
* [Code in JupyterLab](https://github.com/tripleee19/Autism-Screening-in-Adults/blob/main/Project_File.ipynb)
