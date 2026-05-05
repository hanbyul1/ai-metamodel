# AI Metamodel

This repository contains the metamodel artifacts and supporting data used in the study of AI system metamodeling for software engineering.

---

## Repository Contents

- `ai-metamodel.mdj`
  StarUML model file containing the full metamodel definitions, including:
  - Core metamodel
  - Model metamodel
  - Layer metamodel
  - Training metamodel
  - Pipeline and related extensions  

- `case-study-data.xlsx`
  Dataset used for coverage analysis across multiple AI system case studies (e.g., LLaMA, BLOOM, Agentic Transformer).  
  Includes:
  - Instance-to-metaclass mappings  
  - Coverage counts (Ci, Cm)  
  - Supporting analysis data  

- `agentic-transformer-v15-ROBERTaTokenizer...`
  Implementation artifact related to the Agentic Transformer case study.

---

## Purpose

This repository supports a metamodeling approach that:

- Defines **domain-agnostic abstractions** for AI systems  
- Enables **systematic modeling and analysis** of AI architectures  
- Supports **model-driven design** and extensibility  
- Provides **traceable mappings** between real-world AI systems and metamodel constructs  

---

## Metamodel Overview

The metamodel is structured into modular components:

- Core – fundamental modeling abstractions  
- Model – AI model architecture and design patterns  
- Layer – computational building blocks (e.g., attention, normalization)  
- Training – learning paradigms and optimization processes  
- Pipeline – system-level orchestration and workflows  

All models are defined using UML-based metamodeling in StarUML.

---

## Reproducibility

- The StarUML file (`.mdj`) provides the complete metamodel specification  
- The Excel dataset provides all data used for coverage analysis  

These artifacts enable replication of:
- Coverage mapping  
- Metamodel instantiation analysis  
- Case study evaluation  

---

## Tools

- [StarUML](https://staruml.io) – used to create and edit the metamodel  
- Microsoft Excel (or compatible tools) – for dataset analysis  

---

## Related Work

This repository accompanies research on:
- AI system metamodeling  
- Model-driven engineering for AI  
- Architectural abstraction of machine learning systems  

---

## License

This repository is provided for academic and research purposes.

---

## Contact

For questions or collaboration inquiries, please contact the repository owner.
