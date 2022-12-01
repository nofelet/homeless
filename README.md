# "homeless" repo
This repository presents anonymized dataset and experiment results described in paper *"Rehabilitating Homeless: Dataset and Key Insights"* (arxiv link will follow).
The dataset is based on more than 9 years' experience and data collection of **"Nochlezhka"** non-government organization helping homeless people.
You can visit them at https://homeless.ru/en/how_to_help/ and play your role in the noble cause of helping the homeless.
What does this repo consist of?
* *Appendix.pdf* - appendix to the original "Rehabilitating Homeless: Dataset and Key Insights" paper containing supplementary tables with detailed description of dataset features and NaN statistics featurewise.
* *all_evens_anonymized.csv* - events (visits to humanitarian projects or entering social contracts) for each person (anonymized and represented by unique IDs) with dates.
* *anonymized_contracts.csv* - social contracts for each person (anonymized and represented by unique IDs) in more detail - with contract statuses, start dates and end dates.
* *anonymized_ids_map.csv* - representation of each person (each row is a person) by a pair of IDs (one for social contracts, one for humanitarian projects - one person may have either one or both IDs).
* *contract_status.csv* - description of numerical contract status IDs used in the dataset.
* *contract_types.csv* - description of numerical contract type IDs used in the dataset.
* *final_with_onehot_types_all_221020.csv* - the dataset "body" - social contract events with all features extracted from "Nochlezhka" database, along with contract statuses and results.
* *nochlezhka_rel_2.ipynb* - experiments described in the paper, for the sake of reproducibility.
