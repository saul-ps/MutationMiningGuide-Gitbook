# Mutations

This page shows the project variants related to the following genomic databases

### Clinvar

![](../../../.gitbook/assets/mutations-clinvar.png)

Initially, only variants that include the word pathogen in the CLINSG column are shown, to show all variants click on the "show all data" button.

| Column name        | Description                                                                                                                                                             |
| ------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Chr                | Chromosome number                                                                                                                                                       |
| Start              | Start position                                                                                                                                                          |
| Ref                | Reference allele                                                                                                                                                        |
| Alt                | Alternative allele                                                                                                                                                      |
| Genotype           | Sample genotype                                                                                                                                                         |
| IGV                | Integrative Genomic Viewer                                                                                                                                              |
| avsnp150           | Single-nucleotide polymorphism name                                                                                                                                     |
| IDClinvar          | Variation ID in Clinvar                                                                                                                                                 |
| Func.refGene       | Regions (e.g., exonic, intronic, non-coding RNA)) that one variant hits                                                                                                 |
| Gene.refGene       | Gene name associated with one variant                                                                                                                                   |
| AF\_popmax         | Maximum allele frequency across populations                                                                                                                             |
| CLNDN              | Clinical Disease Name                                                                                                                                                   |
| CLNSIG             | Clinical Significance                                                                                                                                                   |
| ExonicFunc.refGene | Exonic variant function, e.g., nonsynonymous, synonymous, frameshift insertion                                                                                          |
| CLNREVSTAT         | Clinical Review Status                                                                                                                                                  |
| AAChange.refGene   | Amino acid change. For example, SAMD11:NM\_152486:exon10:c.T1027C:p.W343R stands for gene name, Known RefSeq accession, region, cDNA level change, protein level change |
| CLNDISDB           | Clinical Source Database and ID                                                                                                                                         |

### Clinical Genome

![](../../../.gitbook/assets/mutations-clinical-genome.png)

| Column name        | Description                                                                                                                                                             |
| ------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Chr                | Chromosome number                                                                                                                                                       |
| Start              | Start position                                                                                                                                                          |
| Ref                | Reference allele                                                                                                                                                        |
| Alt                | Alternative allele                                                                                                                                                      |
| Genotype           | Sample genotype                                                                                                                                                         |
| IGV                | Integrative Genomic Viewer                                                                                                                                              |
| avsnp150           | Single-nucleotide polymorphism name                                                                                                                                     |
| IDClinvar          | Variation ID in Clinvar                                                                                                                                                 |
| Func.refGene       | Regions (e.g., exonic, intronic, non-coding RNA)) that one variant hits                                                                                                 |
| Gene.refGene       | Gene name associated with one variant                                                                                                                                   |
| AF\_popmax         | Maximum allele frequency across populations                                                                                                                             |
| CLNDN              | Clinical Disease Name                                                                                                                                                   |
| CLNSIG             | Clinical Significance                                                                                                                                                   |
| ExonicFunc.refGene | Exonic variant function, e.g., nonsynonymous, synonymous, frameshift insertion                                                                                          |
| CLNREVSTAT         | Clinical Review Status                                                                                                                                                  |
| AAChange.refGene   | Amino acid change. For example, SAMD11:NM\_152486:exon10:c.T1027C:p.W343R stands for gene name, Known RefSeq accession, region, cDNA level change, protein level change |
| CLNDISDB           | Clinical Source Database and ID                                                                                                                                         |

### PharmGKB

![](../../../.gitbook/assets/mutations-pharmgkb.png)

Initially, only variants with evidence level 1 or 2 are shown, to show all variants click on the show all data button.

| Column name            | Description                                                                                                                                                                                                             |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| PhenotypePharm         | Phenotypes in the variant/allele-drug association. For example, if the association was found in patients with a particular phenotype (disease), or if the variant/allele-drug combination causes a particular phenotype |
| PhenotypeCategoryPharm | Association phenotype. Options: toxicity, efficacy, dosage, metabolism/PK, PD, other                                                                                                                                    |
| Drugs                  | Drugs associated with the variant/allele                                                                                                                                                                                |
| SNPS                   | Single-nucleotide polymorphism name                                                                                                                                                                                     |
| Genotype               | Sample genotype                                                                                                                                                                                                         |
| Evidence               | Levels 1A-4 with 1A being the highest level of evidence; more information found on [PharmGKB](https://www.pharmgkb.org/page/clinAnnLevels)                                                                              |
| IDPharmGKB             | The unique PharmGKB ID number for the annotation                                                                                                                                                                        |
| Func.refGene           | Regions (e.g., exonic, intronic, non-coding RNA)) that one variant hits                                                                                                                                                 |
| Gene.refGene           | Gene name associated with one variant                                                                                                                                                                                   |
| AF\_popmax             | Maximum allele frequency across populations                                                                                                                                                                             |
| ExonicFunc.refGene     | Exonic variant function, e.g., nonsynonymous, synonymous, frameshift insertion                                                                                                                                          |
| AAChange.refGene       | Amino acid change. For example, SAMD11:NM\_152486:exon10:c.T1027C:p.W343R stands for gene name, Known RefSeq accession, region, cDNA level change, protein level change                                                 |

### GWAS Catalog

![](../../../.gitbook/assets/mutations-gwas.png)

Initially, only variants that not include some words in the DISEASE.TRAIT column, are exonic and have more than one article associated with more than ten annual citations, to show all variants click on the show all data button.

| Column name        | Description                                                                                                                                                                                                                                                                                      |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| CHR\_ID            | Chromosome number                                                                                                                                                                                                                                                                                |
| CHR\_POS           | Start position                                                                                                                                                                                                                                                                                   |
| REF                | Reference allele                                                                                                                                                                                                                                                                                 |
| RISK.ALL           | Alternative allele                                                                                                                                                                                                                                                                               |
| Genotype           | Sample genotype                                                                                                                                                                                                                                                                                  |
| IGV                | Integrative Genomic Viewer                                                                                                                                                                                                                                                                       |
| SNPS               | Single-nucleotide polymorphism name                                                                                                                                                                                                                                                              |
| RISK.ALL.FREQ      | Reported risk/effect allele frequency associated with strongest SNP in controls (if not available among all controls, among the control group with the largest sample size). If the associated locus is a haplotype the haplotype frequency will be extracted                                    |
| URL                | Link to publication GWAS catalog                                                                                                                                                                                                                                                                 |
| DISEASE.TRAIT      | Disease or trait examined in the GWAS                                                                                                                                                                                                                                                            |
| Func.refGene       | Regions (e.g., exonic, intronic, non-coding RNA)) that one variant hits                                                                                                                                                                                                                          |
| REPORTED.GENE.S.   | Gene(s) reported by author                                                                                                                                                                                                                                                                       |
| P.VALUE            | Reported p-value for strongest SNP risk allele (linked to dbGaP Association Browser). Note that p-values are rounded to 1 significant digit (for example, a published p-value of 4.8 x 10-7 is rounded to 5 x 10-7)                                                                              |
| OR.or.BETA         | Reported odds ratio or beta-coefficient associated with strongest SNP risk allele. Note that if an OR <1 is reported this is inverted, along with the reported allele, so that all ORs included in the Catalog are >1. Appropriate unit and increase/decrease are included for beta coefficients |
| AF\_popmax         | Maximum allele frequency across populations                                                                                                                                                                                                                                                      |
| PUBMEDID           | PubMed identification number                                                                                                                                                                                                                                                                     |
| ExonicFunc.refGene | Exonic variant function, e.g., nonsynonymous, synonymous, frameshift insertion                                                                                                                                                                                                                   |
| STUDY              | Title of manuscript the GWAS is included in                                                                                                                                                                                                                                                      |
| AAChange.refGene   | Amino acid change. For example, SAMD11:NM\_152486:exon10:c.T1027C:p.W343R stands for gene name, Known RefSeq accession, region, cDNA level change, protein level change                                                                                                                          |
| N\_ART             | Number of articles associated with the publication                                                                                                                                                                                                                                               |
| N\_CIT             | Number of citations associated with the publication                                                                                                                                                                                                                                              |
| N\_CIT\_Y          | Number of citations per year associated with the publication                                                                                                                                                                                                                                     |
