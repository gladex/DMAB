## DMAK: Differential-Methylation Annotation Knowledgebase

This GitHub repository is to deposit the Pan-Cancer DMAK (Differential-Methylation Annotation Knowledgebase) results for our recent ENCODE project. DMAK contains the following information:

### D1_methylValue_C&T:
Statistical information detected for sequencing read coverage, number of Cs and Ts of for the 688,445 CpG sites across all cancer and normal cell lines listed above. For consistence, all DNA methylation data sets from ENCODE Consortium are based on the RRBS platform;

### D2_methylValue_Percentage:
Analysis and annotation results for the methylated CpG sites (mCpG), which provide the methylation percentage value for all mCpG sites across the mentioned cell lines. The higher percentage value indicates the higher methylation status, and vice versa;

### D3_T47D.methyl.DVQV.25p:
Analysis and annotation results for the significant differentially-methylated CpG sites (SDMC) with reference to one cell type, here we selected T-47D as the study case. The results are further filtered based on the lifted methylation difference threshold (at least 25% methylation difference for the paired groups). And the SDMC list contains 106,252 DMCs, together the related statistical p-value and adjusted q-value are also provided; 

### D4_T47D_SigDMR:
Statistical analysis and annotation results for the differentially-methylated regions (DMR) with reference to one cell type, for consistence we selected T-47D as the case. We identified 16,277 DMR candidates from all the DMCs, with the adjusted q-value <= 0.01, CpG base methylation difference cutoff, 25, and DMR mean methylation difference cutoff, 20. Within those candidates, 8,936 entries present hyper-methylated and 7,341 with hypo-methylated status. With the lifted thresholds, namely adjusted q-value <= 0.001, differentially-methylated CpG base count >= 5, we further detected 7,537 significant DMRs (Sig-DMRs), where 3,512 entries are significantly hypermethylated-DMRs (Sig-Hyper-DMRs), and 4,025 significantly hypomethylated-DMRs (Sig-Hypo-DMRs);

### D5_T47D_SigDMR.HYPER:
Statistical analysis and annotation results for the significantly hypermethylated-DMRs (Sig-Hyper-DMRs) with reference to T-47D cell type;

### D6_T47D_SigDMR.HYPO:
Statistical analysis and annotation results for the significantly hypomethylated-DMRs (Sig-Hypo-DMRs) with reference to T-47D cell type;

### D7_T47D_methyGenes:
Statistical analysis and annotation results for the identified genes from all DMRs (hyper-DMRs and hypo-DMRs) with reference to T-47D cell type;

### D8_GO_HyperDMR:
Gene Ontology annotation results for the TSGs identified from hyper-DMRs;

### D9_GO_HypoDMR:
Gene Ontology annotation results for the TSGs identified from hypo-DMRs.

## F1_Hyper_TSG_All.png
Functional association network for tumor suppressor genes (TSG) identified from hyper DMRs.

## F2_Hypo_TSG_All.png
Functional association network for tumor suppressor genes (TSG) identified from hypo DMRs.

Any citation or re-usage of the resources, please cite properly or contact me first for more details.

(c) BHT (bh.tang@outlook.com)
