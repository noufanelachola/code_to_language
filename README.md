# AI-Powered Code-to-English Translator for Healthcare Software

This project develops an AI-based “Code-to-English Translator” to explain Python code used in healthcare software systems. It reduces the black-box nature of medical algorithms by converting code snippets (e.g., dosage calculators, risk scores, billing logic) into plain English descriptions that doctors and nurses can understand.[cite:5]

## Problem Statement

Modern healthcare systems rely on complex Python programs to compute patient dosages, disease risk scores, and medical billing calculations. Medical professionals often cannot interpret the underlying source code, which creates a black-box situation and reduces trust and transparency in automated decisions.[cite:5]

## Objectives

- Build a CodeBERT-based tool in Python (Google Colab) that reads Python snippets containing medical logic.[web:42]
- Generate clear, human-readable English explanations of what the code does.
- Provide a simple Gradio interface for interactive code explanation in the browser.[web:23]
- Demonstrate how AI can improve interpretability and trust in healthcare software systems.

## Technologies

- Python 3.x
- Google Colab
- Hugging Face Transformers (microsoft/codebert-base)
- Gradio
