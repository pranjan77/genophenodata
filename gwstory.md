## SDK and Science Target Functionality - post GWAS functional analysis

### Summary
The methods in this service will help users to explore Genomewide association analysis results, multiple ways to visualize the results, integrate with omics datasets, expedite data mining and aid hypotheses building.

### Story/Description 
Genome wide association analysis (GWAS) identifies statistically significant single nucleotide polymorphisms (SNPs) related to phenotype / trait of interest. Post GWAS analyses which is going from list of SNPs to a more complete biological story is a major bottleneck. Most of these analysis require manual data extraction and integration with other data types including expression data and pathway data. Just sharing of this dataset is a big challenge for the community. 

GWAS populations and thousands of population level measurements are available for various plant species including Arabidopsis, Populus, Medicago, Sorghum, Maize, Soybean, Foxtail millet, Rice, Switchgrass etc. It is a new functionality and will help us target a different set of researchers leading to citations.


This product will have following methods.

#### Data types and uploader methods

    upload SNPs
    upload SNP statistics for each phenotype
    upload phenotype data
    upload population metadata (eg. latitude, longitude, climate, soil)
    upload expression data (already implemented)
    upload network data (not defined yet?.. Something for future)
    
    
#### Supported narrative methods in the short term

Mockup narrative here: https://appdev.kbase.us/narrative/ws.179.obj.1

    Associate SNPs to a genome
    Display GWAS results
        static manhattan plot
        Interactive manhattan plot
        QQ-Plot
        Box plot distribution of phenotypes
        Phenotypic values displayed on world map
    Identify gene list corresponding to SNPs
    Calculate and View LD in a region of the genome
    Gene score analysis 
    Pathway enrichment analysis
    Gene ontology enrichment analysis
    Associate genelist to expression data and visualize as heatmap
    Associate gene list to user uploaded network data
    Identify common SNPs and genes across multiple related phenotype categories
    
#### Supported narrative methods with external dependencies (longer term)

        Visualize SNPs in genome browser
        Predict functional effect of SNP (SIFT , snpEFF etc.) 
        Analysing non-coding SNPs by associating it to a database of conserved non-coding sequences and regulatory motifs
    
