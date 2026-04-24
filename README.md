# Humboldt marten genomics project

Welcome to the GitHub page for this project! This is where I will be posting updates, results, and details about the analyses I'm running.

See the proposal document for an overview of the project goals and approaches: https://github.com/savanahbird/coastal_martens/tree/main/Humboldt_WGS_proposal.pdf

Preliminary results from sequencing data mapped to the <i>M. flavigula</i> assembly: 
https://github.com/savanahbird/coastal_martens/tree/main/Results_update_260331.pdf

See Wiki page for summary of bioinformatics used to do run analyses: https://github.com/savanahbird/coastal_martens/wiki/

### Sneak peak at some updated results with data mapped to new <i>M. caurina humboldtensis</i> assembly
#### Heterozygosity
<img alt="Het_boxplot_MCH" src="https://github.com/user-attachments/assets/8ac5aa38-b359-476e-8c2d-c20d509ff57b" width="75%"/>

Heterozygosity estimates are much <b>lower</b> than they were when we used <i>M. flavigula</i> as a reference. We think that the deep divergence between <i>M. caurina</i> and <i>M. flavigula</i> resulted in mismapping which caused spurious heterozygosity.

#### Inbreeding
<img alt="ROH_bcftools_all_MCH" src="https://github.com/user-attachments/assets/8d9d822b-e318-47d6-95f7-d288dde65b73" width="75%"/>

From left to right, groups are: <i>M. americana</i> (Colella et al. 2021), Colorado/Washington (Colella et al. 2021), OR Cascades, CA North, OR South, OR Dunes South, OR Dunes North. Fraction of the genome occuring within a long ROH is <b>higher</b> than it was when we used <i>M. flavigula</i> as a reference. We think that the spurious heterozygosity spikes were breaking up long ROH.
