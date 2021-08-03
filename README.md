# combinatory_prediction
Combinatory prediction method with various insilico predictors


Paper: https://peerj.com/articles/8106/

Scripts and description for combinatory insilico prediction 


There are 3 script:

**parse_clinvar_db.pl** - This scripts extracts SNVs (corresponding to hg19).

**extractscore_cln-dbnsfp.pl**- This scripts runs the Java script to get information from dbNSFP datasource.

**collecting_singval.pl**- Clean up and format the input file


Please download the dbnsfp source: https://sites.google.com/site/jpopgen/dbNSFP

We used the final output file from "**collecting_singval.pl**" and used it as a test data in **WEKA** for classifcation. The training dataset can also be found in https://dfzljdn9uc3pi.cloudfront.net/2019/8106/1/Weka_training_dataset.csv

