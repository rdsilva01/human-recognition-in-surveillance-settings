# Human Recognition in Surveillance Settings (HRSS)

This notebook implements and compares multiple methods for human recognition in surveillance images:
- Baseline Model: A ResNet50 CNN trained on facial embeddings.
- Vision-Language Analysis: Uses LLaVA and GPT-4o to provide textual interpretations of visual similarity.
- Result Reporting: Generates markdown reports combining model scores and textual outputs.

Key Features
- Image comparison using facial embeddings.
- Visual-textual reasoning via GPT-4o and LLaVA.
- Markdown report generation with embedded image evidence and analysis.

## Requirements
- Python 3.10+
- torch, transformers, PIL, openai, llava, etc.

## Usage
Run the notebook step by step:
1.	Load image pairs.
2.	Train the model (or use the trained one provided)
4.	Query GPT-4o or LLaVA.
3.	Generate embeddings.
5.	Generate a report in .md format.
