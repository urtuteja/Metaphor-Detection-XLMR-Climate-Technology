# Metaphor-Detection-XLMR-Climate-Technology

This repository contains the materials for the project **_Assessing XLM-R for Metaphor Detection in Climate Technology Discourse_**.

---

## Project Report

For a detailed explanation of the project, see the full report:  [Final_Report.pdf](./Final_Report.pdf)

---

## Repository Structure

- **`Metaphor-Detection-XLMR-Continued-Pretraining.ipynb`**  
  Main notebook for metaphor detection experiments with and without continued pre-training.

- **`Statistics.ipynb`**  
  Provides code to generate statistics on the data used in the project.

- **`/Data`**  
  Contains all datasets used for continued pre-training as well as model testing.  
  *Note:* The training file is too large to include here but can be accessed at the original repository: [lwachowiak/Metaphor-Detection-XLMR on HuggingFace](https://huggingface.co/lwachowiak/Metaphor-Detection-XLMR)

- **`/Results (HTML)`**  
  Contains HTML outputs of the notebooks for quick viewing.

- **`/continued-pretraining`**  
  Contains outputs generated during the continued pre-training process.

- **`/Error Analysis`**  
  Includes files used for an extensive error analysis of the model predictions.
  
---

## Not Included (Due to File Size Limitations)

The following folders were generated while running the code but are not included in this repository:

- **`/metaphor_xlmr_domain_adapted`**  
  Folder created during domain-adaptive pre-training.

- **`/metaphor_xlmr_finetuned`**  
  Output folder generated during the fine-tuning stage.

---
