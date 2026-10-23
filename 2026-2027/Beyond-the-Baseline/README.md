<div align="center">

# Beyond the Baseline
### Domain-Specific Vision-Language Models, Clinical Prompting, and Explainable AI for Cancer Classification

[![KSU](https://img.shields.io/badge/Kennesaw_State_University-FDBB30?style=for-the-badge&labelColor=000000)](https://www.kennesaw.edu/)
[![iCARE Lab](https://img.shields.io/badge/iCARE_Lab-0E7490?style=for-the-badge)](https://icare-lab.org/)
![SSP](https://img.shields.io/badge/Sophomore_Scholars-2026–2027-1D4ED8?style=for-the-badge)

**School of Data Science and Analytics | Intelligent Computing for Advanced Research in Healthcare (iCARE) Lab**  
**Lab Website:** [icare-lab.org](https://icare-lab.org/)

</div>

---

## Main Research Question

> **Building upon our Year 1 ResNet50 and general CLIP baselines, how can clinical prompt engineering, domain-specific medical VLMs (PLIP & BiomedCLIP), parameter-efficient fine-tuning (LoRA), and explainable heatmaps improve diagnostic accuracy and interpretability across histopathology and dermatoscopy cancer datasets?**

### Research Workflow

`Year 1 Baselines (ResNet50 & CLIP)` → `Clinical Prompt Engineering` → `Medical VLMs (PLIP & BiomedCLIP)` → `Explainable AI (Grad-CAM & Attention Maps)` → `LoRA Fine-Tuning & Report Generation` → `NCUR & Symposium Manuscript`

---

## Quick Access: Coding Notebooks

All coding exercises and model workflows run directly in your browser using **Google Colab**.  
👉 **[Open the `notebooks/` Folder](./notebooks)**

| Date | Module | Topic | Status | Launch in Colab |
| :--- | :--- | :--- | :--- | :--- |
| **Year 1** | **Modules 1–3** | Dataset Splits, ResNet50 Baseline & General CLIP (Zero-Shot, 10-Shot, Linear Probe) | ![Completed](https://img.shields.io/badge/Completed-16A34A?style=flat-square) | *Completed* |
| **Oct 22, 2026** | **Module 4** | Clinical Prompt Engineering: Visual vs. Diagnostic Text Prompts in CLIP | ![Completed](https://img.shields.io/badge/Completed-16A34A?style=flat-square) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iCARE-Lab/Sophomore-Scholar-Program/blob/main/2026-2027/Beyond-the-Baseline/notebooks/Module_4_Clinical_Prompt_Engineering.ipynb) |
| **Oct 28, 2026** | **Module 5** | Domain-Specific Medical VLMs: Benchmarking **PLIP** vs. **OpenAI CLIP** | ![Completed](https://img.shields.io/badge/Completed-16A34A?style=flat-square) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iCARE-Lab/Sophomore-Scholar-Program/blob/main/2026-2027/Beyond-the-Baseline/notebooks/Module_5_Domain_Specific_Medical_VLMs.ipynb) |
| **Nov 11, 2026** | **Module 6** | 10-Shot Adaptation & Hybrid Prompt-Visual Ensembling | ![Completed](https://img.shields.io/badge/Completed-16A34A?style=flat-square) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iCARE-Lab/Sophomore-Scholar-Program/blob/main/2026-2027/Beyond-the-Baseline/notebooks/Module_6_Prompt_Ensembling_and_Few_Shot_Adaptation.ipynb) |
| **Nov 25, 2026** | **Module 7** | Explainable Medical AI (XAI): Grad-CAM & VLM Patch Heatmaps | ![Completed](https://img.shields.io/badge/Completed-16A34A?style=flat-square) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iCARE-Lab/Sophomore-Scholar-Program/blob/main/2026-2027/Beyond-the-Baseline/notebooks/Module_7_Explainable_Medical_AI_GradCAM_and_Attention.ipynb) |
| **Jan 20, 2027** | **Module 8** | Parameter-Efficient Fine-Tuning (LoRA) for Medical VLMs | ![Completed](https://img.shields.io/badge/Completed-16A34A?style=flat-square) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iCARE-Lab/Sophomore-Scholar-Program/blob/main/2026-2027/Beyond-the-Baseline/notebooks/Module_8_LoRA_Parameter_Efficient_Fine_Tuning.ipynb) |
| **Feb 17, 2027** | **Module 9** | Automated Clinical Pathology Report Generation | ![Completed](https://img.shields.io/badge/Completed-16A34A?style=flat-square) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iCARE-Lab/Sophomore-Scholar-Program/blob/main/2026-2027/Beyond-the-Baseline/notebooks/Module_9_Automated_Clinical_Report_Generation.ipynb) |

---

## Project Roadmap

### Fall 2026: Clinical Prompting, Medical VLMs & Explainability

| Date | Topic |
| :--- | :--- |
| **Oct 7** | Welcome, Year 2 Sophomore research expectations, and project roadmap |
| **Oct 14** | **Review of Year 1 Baselines** — Finalizing ResNet50 vs. OpenAI CLIP manuscript tables & figures |
| **Oct 22** | **Clinical Prompt Engineering (Module 4)** — Visual morphology vs. diagnostic text prompts in CLIP |
| **Oct 28** | **Domain-Specific Medical VLMs (Module 5)** — Benchmarking **PLIP** and **BiomedCLIP** & NCUR 2027 Abstract Submission |
| **Nov 4** | **Cross-Modality Zero-Shot Analysis** — Comparing general vs. medical VLMs on Breast (IDC) and Skin (HAM10000) |
| **Nov 11** | **Prompt Ensembling & 10-Shot Adaptation (Module 6)** — Combining multi-prompt templates in low-data regimes |
| **Nov 18** | **Fall Symposium & Mid-Semester Evaluation** — Presenting comparative VLM findings |
| **Nov 25** | **Explainable Medical AI (Module 7)** — Generating Grad-CAM (ResNet50) and cross-attention heatmaps (VLMs) |
| **Dec 2** | Fall review, manuscript finalization, and preparation for Spring LoRA & Report Generation |

### Spring 2027: Parameter-Efficient Fine-Tuning (LoRA), Report Generation & Dissemination

| Date | Topic |
| :--- | :--- |
| **Jan 13** | **Introduction to Parameter-Efficient Fine-Tuning (PEFT)** — Setting up HuggingFace PEFT for medical VLMs |
| **Jan 20** | **LoRA Fine-Tuning (Module 8)** — Low-Rank Adaptation vs. Linear Probing on Histopathology & Dermatoscopy |
| **Jan 27** | **Full-Dataset vs. Few-Shot LoRA Comparison** — Running complete experimental pipelines |
| **Feb 3** | **Quantitative Evaluation** — Computing Accuracy, Weighted F1-Score, Confusion Matrices, and AUC-ROC |
| **Feb 10** | **Visual Interpretability Analysis** — Validating model attention heatmaps on malignant vs. benign tissue |
| **Feb 17** | **Automated Clinical Report Generation (Module 9)** — Generating structured diagnostic text from cancer images |
| **Feb 24** | **Organize Research Results** — Finalize publication-grade tables, ROC curves, and heatmap figures |
| **Mar 3** | *No meeting — Spring Break* |
| **Mar 10** | **Spring Symposium Oral Abstract Deadline** — Draft methods, results, and conclusions |
| **Mar 17** | **Spring Symposium Poster Abstract Deadline** — Submit abstract and finalize presentation plan |
| **Mar 24** | **NCUR & Symposium Poster Practice** — Practice explaining Medical VLM, Prompting, and XAI findings |
| **Mar 31** | **Presentation Practice and Discussion** — Refine technical and general-audience explanations |
| **Apr 7** | Final Poster Review and Practice |
| **Apr 12–14** | **NCUR 2027 — Present Research in Grand Rapids, Michigan** |
| **Apr 21–23** | **Spring Symposium of Student Scholars — Present Research** |

---

## Prior Foundation & Related Output

- **Published Abstract:** Imran, M., Rojas, A., Zafar, A., & Patil, S. (2026). *"Beyond the Baseline: A Comparative Analysis of Vision-Language Models and ResNet50 for Few-Shot and Full-Data Cancer Classification."* 2026 Spring Southeastern Sectional Meeting of the American Mathematical Society (AMS), Reference ID 60693. [View in AMS Program](https://meetings.ams.org/math/spring2026se/meetingapp.cgi/Paper/60693)

---

## Important Program Dates (2026–2027)

| Date | Event |
| :--- | :--- |
| **Oct 28, 2026** | NCUR 2027 funding/pre-approval abstract deadline — 11:59 PM (Campus Hub) |
| **Nov 18–20, 2026** | Fall Symposium of Student Scholars |
| **Dec 13, 2026** | Scholars Mid-Year Survey due |
| **Mar 10, 2027** | Spring Symposium oral-presentation abstract deadline — 11:59 PM (Campus Hub) |
| **Mar 17, 2027** | Spring Symposium poster/visual/virtual abstract deadline — 11:59 PM (Campus Hub) |
| **Apr 12–14, 2027** | NCUR 2027 — Grand Rapids, Michigan |
| **Apr 21–23, 2027** | Spring Symposium of Student Scholars (Poster, Oral, & Virtual Presentations) |
| **May 2, 2027** | Scholars Year-End Evaluation due (Campus Hub) |

> [!NOTE]
> **Research Team Expectations**
> * Dedicate **5–10 hours per week** to the project and attend weekly meetings.
> * Take ownership of organizing experiments, documenting reproducible results, and tracking metrics.
> * Ask questions early and communicate clearly—our goal is rigorous research, scientific communication, and growth.
