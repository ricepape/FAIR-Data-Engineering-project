# FAIR Data Engineering Project

## Overview  
This repository contains the project for *FAIR Data Engineering*. The goal of the project is to design, build and document a data engineering workflow that aligns with the FAIR principles (Findable, Accessible, Interoperable, Re-usable). It focuses on good data management, reproducible pipelines, metadata, and clear structure. 
Author: Thi Vu, Mohammed Yousuff L.

## Objectives  
- Apply the FAIR principles to a data engineering scenario.  
- Create a structured workflow for data ingestion, processing, metadata generation, and storage.  
- Ensure that data and metadata are documented, versioned, and easily discoverable.  
- Use tools (e.g., Docker, version control, workflow orchestration) to enhance reproducibility.  
- Provide clear documentation so that others can understand, reuse, or extend the workflow.

## Repository Structure  
Here is a high-level look at the main folders and what they contain:

├── Data/ ← raw, interim, processed datasets
├── Metadata/ ← metadata files describing datasets and workflows
├── Ontology/ ← ontology, schema or vocabulary definitions
├── Shapes/ ← SHACL/other shape constraints (for metadata validation)
├── FAIR Data Point/ ← (if applicable) repository or container for FAIR Data Point set-up
├── Docker/ ← Dockerfiles and images for containerised environments
└── README.md ← this file

### Key folders:  
- **Data/**: Contains input data, intermediate results and final output data.  
- **Metadata/**: Holds metadata that describe the datasets, provenance, lineage and any schemas.  
- **Ontology/**: Defines ontologies, controlled vocabularies or linkages used to support interoperability.  
- **Shapes/**: Defines validation rules (e.g., using SHACL or other schema language) to ensure metadata or data adhere to constraints.  
- **Docker/**: Contains the docker files, configurations and environment definitions to reproduce the workflow on any machine.

## License & Acknowledgements  
- License: CC0 1.0
- Acknowledgements: A special regard to our teacher Luiz Bonino for the instruction, and free open sources in order to proceed this project.
