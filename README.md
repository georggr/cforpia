# C-FORPIA Ontology

**C-FORPIA** stands for **Cyber-FORensics Privacy Impact Assessment**. It is a unified ontological framework designed to semantically integrate three critical domains:
- **Cyber Threat Intelligence (CTI)**
- **Digital Forensics Readiness (DFR)**
- **Data Protection Impact Assessment (DPIA)**

## About the Project

This ontology was developed as part of a Master’s thesis at the **University of Skövde, Sweden**. The primary goal of the project is to support risk analysis, forensic preparedness, and privacy compliance automation by offering a semantic foundation that bridges the gap between cybersecurity, data protection, and incident response.

The C-FORPIA ontology was created using the **Web Ontology Language (OWL)** and implemented with the **Protégé** ontology editor. It follows the **Design Science Research (DSR)** methodology to ensure both theoretical rigour and practical relevance.

C-FORPIA also incorporates vocabularies/taxonomies such as the DPV: Legal and DPV: Risk,which are the result of the excellent work of the **Data Privacy Vocabularies and Controls Community Group (DPVCG)**

links: [Community Group](https://www.w3.org/community/dpvcg/) | [GitHub](https://github.com/w3c/dpv/)

## Features

- Semantic integration of CTI, DFR, and DPIA concepts
- Supports automated compliance reasoning
- Enables traceability of security and legal requirements
- Provides a foundation for further extension (e.g. with MITRE ATT&CK, DPV, GDPRtEXT)

## Contents

The repository contains:

- `cforpia_v1.5.rdf`: The main OWL ontology file
- `C-FORPIA-ontology-diagram.png`: a visual overview
- `examples/`: Example of its use in real-world scenarions (to be provided) 

## How to Use

1. Open `cforpia.rdf` using [Protégé](https://protege.stanford.edu/).
2. Use the HermiT or Pellet reasoner to explore inferred relationships.
3. Query the ontology using SPARQL to extract insights across CTI, DFR, and DPIA.
4. Extend the ontology as needed to incorporate domain-specific taxonomies or multilingual terms.

## Citation

If you use C-FORPIA in your research or development, please cite the corresponding Master’s thesis:

> Georgiadis, G. (2025). *C-FORPIA: Towards a Unified Ontology for Cybersecurity and Compliance in the GDPR and AI Act Era*. University of Skövde, Sweden.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

For questions or collaboration opportunities, please contact:

**Georgios Georgiadis, PhD**  
Email: [georgios.georgiadis@ugent.be](mailto:georgios.georgiadis@ugent.be)

---

© 2025 Georgios Georgiadis. All rights reserved.
