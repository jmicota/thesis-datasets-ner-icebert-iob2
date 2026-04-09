# Syntheitic Icelandic dataset for NER anonymization task

This is a dataset of **synthetic** Icelandic messages from patients to clinics.

The description of the process of generation of this dataset, and more statistics about the dataset can be found in this paper: TODO

This dataset has been used for training an anonymization model that can be found in this repository: https://github.com/jmicota/thesis-models-ner-icebert-iob2

This dataset is split to train, test and validation subsets.
It is tagged with **IOB2 scheme** with original labels being:
- AGE_90_PLUS
- CONTACT
- DATE
- ID
- LOCATION
- NAME
- OTHER
- PROFESSION

# Dataset label distribution across splits

| Label        | Train | Validation | Test |
|--------------|------:|-----------:|-----:|
| AGE_90_PLUS  |   384 |         83 |   69 |
| CONTACT      |  8648 |       1830 | 1875 |
| DATE         |  1361 |        292 |  273 |
| ID           |  8608 |       1850 | 1864 |
| LOCATION     |  4906 |       1008 | 1037 |
| NAME         | 13180 |       2868 | 2790 |
| OTHER        |   313 |         87 |   75 |
| PROFESSION   |    14 |          1 |    2 |
