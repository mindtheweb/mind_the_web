# Mind The Web

This repository contains supplementary materials for our research on task-aligned injection attacks against web-use agents powered by LLMs.

## Contents

### [Additional Demos](additional_demos/demos.md)

Visual demonstrations of two payload attacks against browser-use agents:

- **P2 — Exfiltrating Overleaf Project Names**: An attack against Browser-Use that hijacks the agent into extracting project names from the user's pre-authenticated Overleaf session and transmitting them to an attacker-controlled server.
- **P3 — Extracting Browser-Autofilled Credentials**: An attack against Do Browser that manipulates the agent into extracting autofilled Facebook credentials and exfiltrating them.

### [Evaluations](evaluations/)

Training and evaluation code for our injection generation models:

- [`baseline_evaluation.py`](evaluations/baseline_evaluation.py) — Evaluation script for baseline injection generation.
- [`sft_dpo_trainer.ipynb`](evaluations/sft_dpo_trainer.ipynb) — Notebook for SFT and DPO training of the injection generation model.

### [Prompts and Traces](prompts%20and%20traces/)

Prompts used in our pipeline and agent execution traces:

- [`prompts.md`](prompts%20and%20traces/prompts.md) — System prompts for the Injection Creator and the LLM Judge.
- [`traces.md`](prompts%20and%20traces/traces.md) — Malicious and benign execution traces of Browser Use agents using Gemini 2.0.
