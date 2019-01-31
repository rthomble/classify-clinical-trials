# NLP@UCSF Learning Project: Building a Classifier to Categorize Clinical Trials
## Repo Name: classify-clinical-trials

Project Summary: Over the next few months, we want to build an NLP based classifer that will be used to categorize Clinical Trial Descriptions (from clinicaltrials.ucsf.edu/browse) according to the condition/body system they describe.

Our theory is that the text descriptions of similar trials will be similar and we are attempting to test that theory in order to categorize trials that are currently in the "other" bucket. We've decided as a group that, since each trial can have multiple conditions (or sub-categories) and multiple clusters (or main categories) we will structure our analytic dataset to try to predict the cluster (main category) given a condition (sub-category) trial pair. It is an evolving discussion what techniques we plan to use to make this preditive model but we are considering: a standard boolean IR model, Latent Dirichlet Allocation (potentially a supervised version of this), multinomial naive bayes classifier, or perhaps kNN or kMeans clustering. Stay tuned for more information.

## IMPORTANT: Please read this note regarding the data set we will use!

The creator of clinicaltrials.ucsf.edu has asked that we use the *actual production JSON file*.

This file is compressed using GZIP and will expand to a (largish ~150MB) JSON file that you can look through using Firefox/Chrome or your favorite JSON browser.  For more details on working with JSON files, see the UCSF Library's JSON Tutorial <https://github.com/ucsf-ckm/python-json-workshop>.

Please download this file to complete the homework assignments.

We will update this repo with homework assignments and solutions approximately once per month.  Occassionally, we will also add additional iPython notebooks that help address specific techniques or concepts.


