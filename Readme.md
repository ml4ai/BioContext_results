# Bio-Context: Results Repository

### Description of JSON files
The JSON files included in this repository contain the results obtained from our experiment. Each classifier we used has an associated JSON, which contains a list object. The list pertains to the list of features that were selected, and their associated performances by each paper. The performance was measured in terms of True Positives, True Negatives, False Positives and False Negatives.
We have included a folder called `ablation_data/`,  containing the compressed version of each classifier result for the users to view.


### For use with BioContext_experiment
To use the resultant JSON files in this repository with the experiment code present in `BioContext_experiment` please manually unzip each JSON file and leave the unzipped file in the `ablation_data/` directory.
