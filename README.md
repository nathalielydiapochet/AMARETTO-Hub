
<p align="center">
  <a href="https://github.com/broadinstitute/AMARETTO-Hub/">
    <img height="400" src="https://github.com/broadinstitute/AMARETTO-Hub/blob/master/inst/extdata/metadata.png">
  </a>
  <h1 align="center"></h1>
</p>

# AMARETTO-Hub

AMARETTO-Hub is a Knowledge Graph-based software platform that leverages neo4j and shiny to embed and interactively interrogate results generated by the *AMARETTO software toolbox which offers modular and complementary solutions to multimodal and multiscale network-based fusion of multi-omics, clinical, imaging, and perturbation data across studies of patients, etiologies and model systems of cancer.

AMARETTO-Hub provides users with neo4j-embedded shiny interactive representation and querying tools that redirect users to *AMARETTO-generated HTML reports.

(1) The AMARETTO algorithm learns networks of regulatory circuits - circuits of drivers and their target genes - from functional genomics or multi-omics data and associates these circuits to clinical, molecular and imaging-derived phenotypes within each biological system (e.g., model systems or patients).

(2) The Community-AMARETTO algorithm learns subnetworks of regulatory circuits that are shared or distinct across networks derived from multiple biological systems (e.g., model systems and patients, cohorts and individuals, diseases and etiologies, in vitro and in vivo systems)

(3) The Imaging-AMARETTO algorithm maps radiography and histopathology imaging data onto the patient-derived multi-omics networks for imaging diagnostics and prognostics to identify clinically relevant imaging biomarkers and decipher their underlying molecular mechanisms.

(4) The AMARETTO-Hub platform for Knowledge Graph-based embedding of knowledge learned via multimodal and multiscale network-based data fusion in previous steps. In these complex graphs, nodes and edges represent the diverse range of biomedical entities and the relationships between them, respectively. Graph-based embedding enables querying these complex graph-structured representations in a more sophisticated, efficient and user-friendly manner than can otherwise be accomplished by table representations alone.

## Installation

Install from the GitHub repository using devtools:

    install.packages("devtools")
    library(devtools)
    devtools::install_github("broadinstitute/AMARETTO-Hub")

## Running AMARETTO-Hub

## References