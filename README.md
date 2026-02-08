# Functional Annotation and Evolutionary Analysis of a Human Homeobox Protein

## Overview
This project presents a complete **in-silico functional annotation and evolutionary analysis** of a *Homo sapiens* Engrailed-type homeobox protein.  
The workflow integrates **query filtering, BLAST-based homolog identification, conserved domain analysis, Gene Ontology (GO) annotation, multiple sequence alignment (MSA), and phylogenetic inference**.

## Workflow
1. Query sequence filtering and validation  
2. Homolog identification using BLASTp  
3. Domain and family annotation using InterProScan  
4. GO annotation and manual curation  
5. Multiple sequence alignment of homologs  
6. Phylogenetic tree construction from MSA  

## Key Results
- **Protein type**: Engrailed-type homeobox transcription factor  
- **Domain**: Homeobox (InterPro: IPR000747; IPR017970; IPR050720)  
- **Localization**: Nucleus  
- **Function**: Sequence-specific DNA-binding transcription factor  
- **Evidence**: Electronic annotation (IEA) supported by evolutionary conservation  

## Tools Used
- BLASTp (homolog identification)  
- InterProScan (domain & GO annotation)  
- Clustal Omega / MAFFT (MSA)  
- MEGA / IQ-TREE (phylogenetic analysis)  

├── data/
├── blast/
├── interproscan/
├── msa/
├── phylogeny/
├── README.md

## Notes
- GO annotations were manually curated to remove redundancy and retain biologically meaningful terms.
- Phylogenetic analysis was based on MSA of BLAST-identified homologs.

