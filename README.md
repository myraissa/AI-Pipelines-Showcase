# Advanced HuggingFace Pipelines: NLP, Vision, and Beyond

This notebook explores HuggingFace's `different_pipelines` API for machine learning tasks, including sentiment analysis, text generation, translation, summarization, image classification, and text-to-image generation. It’s designed for beginners and advanced users, with GPU acceleration for optimal performance.

## Objectives
- Learn to use HuggingFace pipelines for diverse ML tasks.
- Implement best practices like batching and mixed precision.
- Visualize results with charts and images.

## Setup Instructions
- **Google Colab**: Use a T4 GPU (Runtime > Change runtime type > T4 GPU).
- **HuggingFace Token**: Add `HF_TOKEN` to Colab secrets or environment variables [](https://huggingface.co/docs/hub/security-tokens).

## Table of Contents
1. Sentiment Analysis (Text Classification)
2. Named Entity Recognition (NER) using Hugging Face
3. Question Answering with Context
4. Text Generation
5. Translation and Summarization
6. Zero-Shot Text Classification
7. Text-to-Image Generation
8. Text-to-Speech / Audio Generation

## Prerequisites
- Python 3.8+
- Libraries: `transformers`, `torch`, `diffusers`, `matplotlib`
- Optional: GPU for faster inference
