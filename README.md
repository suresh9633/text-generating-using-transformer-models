# Fantasy Story Generation using a Fine-Tuned Transformer

This project demonstrates the process of fine-tuning a pre-trained GPT-2 model to generate short, creative stories in the fantasy genre. The entire workflow, from data preparation to model training and evaluation, is contained within the `fantasy_story_generator.ipynb` notebook.

## 📝 Project Overview

The primary goal is to create a model that can assist writers and creative individuals by generating story ideas and narrative snippets. This repository serves as a proof-of-concept and an educational tool for understanding the fine-tuning process of large language models.

**Key Features:**
* **Data Preprocessing**: Includes scripts for cleaning and preparing raw text for training.
* **Model Fine-Tuning**: Uses the Hugging Face `transformers` library to fine-tune the `gpt2` model.
* **Text Generation**: A simple interface to generate stories based on custom prompts.

##  limitaciones Important Limitations

This project uses a **very small, simulated dataset of only 3 stories** for demonstration purposes. As a result, the fine-tuned model's ability to generate high-quality, coherent, and creative text is **severely limited**. The output will be simplistic and is not representative of what a properly trained model can achieve with a large, high-quality dataset.

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

* Python 3.8 or higher
* pip (Python package installer)

### Installation

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    cd your-repository-name
    ```

2.  **Create and activate a virtual environment (recommended):**
    ```sh
    python -m venv venv
    # On Windows
    venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate
    ```

3.  **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```

### How to Use

1.  Launch Jupyter Notebook or JupyterLab:
    ```sh
    jupyter notebook
    ```
2.  Open the `fantasy_story_generator.ipynb` file.
3.  Run the cells sequentially to see the entire process from data loading to text generation.

## 🔮 Future Work

* **Acquire a Large Dataset**: The most crucial next step is to train the model on a large and diverse corpus of fantasy stories.
* **Implement Rigorous Evaluation**: Use metrics like Perplexity and conduct human evaluations to properly assess model quality.
* **Experiment with Larger Models**: Fine-tune more powerful models like `gpt2-medium` or other architectures.
* **Build a Simple UI**: Create a simple web interface using Flask or Streamlit to make the generator more accessible.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
