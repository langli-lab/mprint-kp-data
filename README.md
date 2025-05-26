# MPRINT Knowledge portal dataset

This repository hosts MPRINT knowledge portal data.

## MPRINT KB Silver and Gold

The MPRINT knowledge portal employs a dual-version structure to accommodate diverse research and clinical needs. The **MPRINT Silver** version encompasses all <i>automatic BERT-based classifications</i> of the studied population and study types for PubMed publications, whereas the MPRINT Gold version hosts expert-curated knowledge from published results.

## MPIRNT KB Silver

### Tables

| Table     | Description  |
| ------------------ | ----------|
| pmid2drug       | Drugs mentioned for each PubMed record   |
|pmid2disease | Disease-related MeSH heading for each PubMed record|
|pmid2population| Maternal and pediatric including specific sub-population (e.g., fetus, postpartum, etc.) for each PubMed records|
|pmid2study_type| Study types associated with the PubMed records.|

> NOTE:
> 1. We use UMLS CUIs for drugs and diseases
> 2. In study types,
>    
>    PK - Pharmacokenetic study
>    
>    PE - EPidemiological study
>    
>    CT - Clinical trial
## MPRINT KB Gold

### Tables

| Table     | Description  |
| ------------------ | ----------|
| gold_drug_disease_pairs | Expert-curated drug-disease pairs |
| gold_drug_gene_pairs | Expert-curated drug-gene pairs |
| gold_gene_disease_pairs | Expert-curated gene-disease pairs |
