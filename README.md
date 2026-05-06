# CCDB: Cervical Cancer gene DataBase

Welcome to the official repository and documentation overview for the **Cervical Cancer gene DataBase (CCDB)**, a manually curated catalog of experimentally validated genes and microRNAs involved in the various stages of cervical carcinogenesis. This resource serves as a specialized platform for researchers and clinicians to explore the molecular mechanisms underlying one of the most common malignancies affecting women worldwide.

**Web Server:** [http://crdd.osdd.net/raghava/ccdb](http://crdd.osdd.net/raghava/ccdb)


## Citation

Agarwal, S. M., Raghav, D., Singh, H., & Raghava, G. P. S. (2011). 
**CCDB: a curated database of genes involved in cervix cancer.** 
*Nucleic Acids Research*, 39 (Database issue), D975–D979. 
[https://doi.org/10.1093/nar/gkq1024](https://doi.org/10.1093/nar/gkq1024)


## About the Database

CCDB is the first specialized resource of its kind, developed to address the lack of integrated data focused specifically on cervical cancer. It consolidates information on genes linked to cancer causation processes such as methylation, gene amplification, mutation, polymorphism, and changes in expression levels.

The database integrates data from:
*   **Primary Literature:** Extensive manual searches of the PubMed database.
*   **External Repositories:** Data integrated from Homologene, HPRD, HGNC, and PharmaGKB.


## Key Features

### Comprehensive Dataset
*   **537 unique genes** involved in different stages of cervical carcinogenesis.
*   Experimentally validated **microRNAs (miRNAs)** with documented target genes and altered expression profiles.
*   **69 hypermethylated genes**, providing more extensive coverage than general methylation databases like PubMed.

### Rich Annotations
Each record includes:
*   **Gene Architecture:** Schematic views of exon-intron structures.
*   **Sequence Data:** mRNA, CDS, and protein sequences, including various isoforms[cite: 1].
*   **Functional Insights:** Gene Ontology (GO) terms (molecular function and biological process).
*   **Evolutionary Context:** Homology relationships and multiple sequence alignments across eukaryotic genomes.
*   **Supporting Evidence:** Manually curated literature references with PubMed IDs (PMIDs).

### Built-in Tools
*   **Customized BLAST:** Search user-defined queries against database sequences to characterize orphan or homologous sequences.
*   **Search & Browse:** Query by gene name, ID, or chromosome, or browse by alphabetical order and biological category.

---

## Overview

CCDB is organized into six primary relational tables to ensure data integrity and ease of access:
1.  **Gene Detail:** Mapping between different gene and protein identifiers.
2.  **Homology:** Orthology relationships derived from Homologene.
3.  **Reference:** Manually curated evidence and sample collection details.
4.  **GO Table:** Functional classifications.
5.  **Sequence:** Location and sequences for mRNA, CDS, and proteins.
6.  **Structure:** 3D protein structure information.

---

## Applications

*   **Molecular Discovery:** Identifying potential biomarkers for cervical cancer progression.
*   **Comparative Oncology:** Comparing genes common across different cancers (e.g., lung or prostate) versus those unique to the cervix.
*   **Therapeutic Research:** Understanding enriched biological processes like signal transduction (26%) and nucleic acid metabolism (17%) to develop novel strategies.
  
## Contact & Authors

**Prof. G.P.S. Raghava**
raghava@imtech.res.in
Bioinformatics Centre, Institute of Microbial Technology (IMTECH), Chandigarh, India.

## License

This database is distributed under the **Creative Commons Attribution Non-Commercial License (CC BY-NC 2.5)**.
