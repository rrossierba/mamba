# Fine-Tuning Mamba: An Alternative to Transformers

**Project Overview**

This repository contains a **Jupyter notebook** developed as the final project for the *Deep Learning and Neural Network Architectures* course at the University of Brescia.
The authors are cited in the notebook.

The work explores the **Mamba architecture**, a recent alternative to transformers based on **State Space Models (SSMs)**.
The main goal was to evaluate whether **fine-tuning techniques** can improve the performance of small-scale Mamba models under limited computational resources (Google Colab with free plan).

---

**What's Inside**

* **Introduction to Mamba**: key concepts and differences from transformers
* **Tools and Frameworks**
    * Hugging Face (models, datasets, and training workflows)
    * LM-Eval (evaluation metrics)
    * Google Colab (experimental environment)
* **Datasets**: PiQA and ARC-e
* **Fine-tuning approaches**:

  * Supervised Fine-Tuning (SFT)
  * Direct Preference Optimization (DPO)
  * LoRA (Low-Rank Adaptation)
* **Results**: comparison with those reported in the original Mamba paper

---

**Why Mamba?**

Unlike transformers, Mamba leverages **State Space Models**, enabling:

* Greater computational efficiency
* Better scalability to longer contexts
* Emerging industrial adoption (e.g., *Mistral Codestral* for code generation)

This project focuses on **Mamba**, although a newer version -Mamba 2- was released, but not compatible with Hugging Face's Transformer library.

---

**Notes**

The notebook also serves as the **final written report** for the course, combining both theoretical explanations and implementation details.
All references and citations are included directly in the notebook.