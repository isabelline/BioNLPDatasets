# BioNLPDatasets
Repo for Bio NLP Resources

# Contents
* Named Entity Recognition
* Named Entity Normalization
* Relation Extraction
* Large Scale Pubmed Corpus

## Named Entity Recognition
* Drug Protein NER
### Disease

* [NCBI Disease Corpus](https://www.ncbi.nlm.nih.gov/CBBresearch/Dogan/DISEASE/): 793 PubMed abstracts
6,892 disease mentions
790 unique disease concepts
Medical Subject Headings (MeSH )
Online Mendelian Inheritance in Man (OMIM )
91% of the mentions map to a single disease concept
divided into training, developing and testing sets.

### Mutation Mentions of various kinds (Protein, DNA...)

* [tmVAR](https://www.ncbi.nlm.nih.gov/CBBresearch/Lu/Demo/tmTools/download/tmVar/tmVarCorpus.zip): tmVar Corpus contains 500 PubMed articles manually annotated with mutation mentions of various kinds.

### Chemical Disease Interaction

* [BC5CDR](https://github.com/cambridgeltl/MTL-Bioinformatics-2016/tree/master/data/BC5CDR-IOB): BC5CDR corpus consists of 1500 PubMed articles with 4409 annotated chemicals, 5818 diseases and 3116 chemical-disease interactions.

* [CDT](): The weakly-labeled corpus used in (Peng et al., 2016) consists of 18,410 abstracts and 33,224 CID relations. The raw data was extracted from curated data in the CTD-Pfizer collaboration with document-level annotations of drug-disease and drug-phenotype interactions.

### Chemical and Drug

* [BioCreative IV Chemical and Drug (BC4CHEMD)]()

## Relation Extraction

### Gene-Disease

* [GAD](http://ibi.imim.es/befree/#corpora): The Genetic Association Database (GAD) is an archive of human genetic association studies of complex diseases, including summary data extracted from publications on candidate gene and GWAS studies. We use GAD for the development of a corpus on associations between genes and diseases (downloaded on January 21st, 2013).

* [EU-ADR](http://ibi.imim.es/befree/#corpora): The corpus has been annotated for drugs, disorders, genes and their inter-relationships. For each of the drug-disorder, drug-target, and target-disorder relations three experts have annotated a set of 100 abstracts.


### Chemical-Protein

* [ChemProt](): 

### Protein-Protein

* [PPI](http://mars.cs.utu.fi/PPICorpora/): This is a new, and much improved, binarization of BioInfer as reported in Heimonen et al., Complex-to-Pairwise Mapping of Biological Relationships using a Semantic Network Representation. 

### Drug-Drug Interaction

* [DDIExtraction2013](https://www.cs.york.ac.uk/semeval-2013/task9/index.php%3Fid=data.html): 

### Drug-ADE
* [ADE](https://github.com/trunghlt/AdverseDrugReaction/tree/master/ADE-Corpus-V2): Development of a benchmark corpus to support the automatic extractionof drug-related adverse effects from medical case reports

* [TAC2017](https://bionlp.nlm.nih.gov/tac2017adversereactions/): The DDIExtraction2013 Shared Task focuses on extraction of drug-drug interactions. 

* [SMM4H](https://data.mendeley.com/datasets/rxwfb3tysd/2): Fourth Social Media Mining for Health (#SMM4H) Shared Task at ACL 2019

* [ADRMine](http://diego.asu.edu/downloads/publications/ADRMine/downloa%20d_tweets.zip): Corpus from Analysis of the effect of sentiment analysis on extracting adverse drug reactions from tweets and forum posts

## Large Scale Pubmed Corpus

### Pubmed

* [Pubmed Phrases](https://ftp.ncbi.nlm.nih.gov/pub/lu/PubMedPhrase/PubMed_Phrases.tar.gz): The dataset contains a collection of 705,915 PubMed Phrases (Kim et al., 2018) that are beneficial for information retrieval and human comprehension. 


### Useful Links
- http://biocreative.sourceforge.net/bio_corpora_links.html
