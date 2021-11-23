# Concept extraction from medical notes using NLP 
This repository contains an iPython notebook demonstrating an approach to extracting pre-defined medical concepts that are affecting a patient from their medical notes. Some anonymous sample data is also provided to demonstrate how the NLP pipeline can be used. 

The data is pre-processed and then medical notes are passed through an NLP pipeline to identify any medical concepts of interest present. These are then analysed for negation and relevance to the patient and the results of the extraction are outputted in the form of a set of True or False labels for all of the inputted medical concepts for each patient.

## Requirements
To install the required Python modules navigate to the directory containing the cloned repository and run:
<pre><code>pip install -r requirements.txt</code></pre>

## Running the notebook
To run the notebook, navigate to the directory containing the notebook .ipynb file and the sample_data folder and run:
<pre><code>jupyter notebook</code></pre>
Then click on freetext_nlp_extraction.ipynb
