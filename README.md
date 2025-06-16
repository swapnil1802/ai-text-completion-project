# ai-text-completion-project

This project implements a Generative AI-based text completion application using Hugging Face's inference API. The system interacts with an instruction-tuned large language model to generate responses for a variety of natural language prompts across domains such as factual explanation, creative writing, reasoning, and summarization.

## Model and API Details

- **Model Used**: `HuggingFaceH4/zephyr-7b-beta`
- **Model Type**: Instruction-tuned decoder-only transformer
- **API Platform**: Hugging Face Inference API
- **Authentication**: Token-based access control

## Technologies and Libraries
- Python (Google Colab)
- `requests`
- `huggingface_hub`
- `transformers`

## Setup Instructions
### Prerequisites

- Hugging Face account: [https://huggingface.co](https://huggingface.co)
- API token with read access: [https://huggingface.co/settings/tokens](https://huggingface.co/settings/tokens)

### Environment Setup

Install required libraries:
```bash
pip install requests huggingface_hub
```
## Usage Instructions

1. Authenticate with Hugging Face:

```python
from huggingface_hub import login
login("your_huggingface_api_token")

## Example Prompt Categories

- Factual explanation (e.g., "Explain photosynthesis to a 10-year-old.")
- Logical reasoning (e.g., "If 5 workers build 5 houses in 5 days...")
- Summarization (e.g., "Summarize the following passage...")
- Creative writing (e.g., "Write a short story about a robot...")
- Instructional simplification (e.g., "Explain recursion like I’m five.")
