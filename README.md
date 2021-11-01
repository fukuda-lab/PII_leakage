# PII Leakage in May 2021
This repository provides some complemental materials for our project on investigating PII leakage-based tracking.

We  provide the dataset about such PII leakage information 
and could be used as a starting point for an in-depth study 
on the web tracking base on authenticated traffic.
This dataset contains a lists of URLs,  first-party senders, third-party receivers,
leakage methods, encoding forms, and PII types
of the PII leakage included in 130 first-party senders in the popular shopping sites in the Tranco top 10K sites.
 
The dataset is collected from an IP address located in Japan in May 2021.

## pii_leakage_202105.csv
| Column Name   | Description                             |
| -----------   | -----------                             |  
|no             |ID of PII leakage URL                    |
|url            |PII leakage URL                          |
|3rd_domain     |Third-party receiver                     |
|http_method    |HTTP request method                      |
|referer        |Referer header                           |      
|cookie         |Cookie header (if any)                   |
|payload_body   |Payload body of an HTTP request (if any) |
|encoding_form  |PII leakage encoding form                |
|leakage_method |PII leakage method                       |
|pii_type       |PII leakage type                         |
|1st_domain     |First-party sender                       | 


***
## Citation
If you use this dataset in your research, please cite our CoNEXT 2021 publication. You can use the following BibTeX.
```
@inproceedings{df2021,
  title={Alternative to third-party cookies: Investigating persistent PII leakage-based web tracking},
  author={Ha Dao and Kensuke Fukuda},
  booktitle={Proceedings on CoNEXT},
  year={2021}
}
```

***
Last update: Monday November 01 06:26:09 JST 2021

