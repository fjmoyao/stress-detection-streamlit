# Stress Detection with Transformers

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://stress-detection-app.streamlit.app/)

![Inference Example](images\stress_inference.gif)

This application leverages the RoBERTa model, an advanced attention-based model from the Transformers family, fine-tuned on Reddit posts to detect indications of stress in written text. By identifying linguistic markers of stress, this tool contributes to mental health initiatives by providing an accessible means to flag potential mental health issues early, potentially preventing the escalation to more severe conditions.

## Key Features
- Utilizes RoBERTa, a state-of-the-art natural language processing model.
- Fine-tuned on a diverse dataset of annotated Reddit posts.
- Implements an easy-to-use interface through Streamlit to demonstrate real-time text classification.

## Requirements
Ensure you have the following prerequisites installed on your system:

- Streamlit
- Pytorch
- Python 3.10 or higher
- Transformers

## Installation
To set up the application on your local machine, follow these steps:

Using `pip`:

```bash
pip install -r requirements.txt
```

**Note**: The application requires a Hugging Face API key. Ensure to include your API key in an `.env` file.


## Running the app
To start the application and explore its capabilities, navigate to the project directory and run:

```bash
streamlit run app_main.py
```

## Dive Into Mental Health Awareness

Explore how subtle linguistic patterns can reflect underlying stress and contribute to broader mental health diagnostics. This tool not only enhances awareness but also provides insights into how language relates to emotional states, helping prioritize mental wellness in everyday communications.

