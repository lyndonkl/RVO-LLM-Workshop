# RVO-LLM Based Sales Agent Workshop

Welcome to the Sales Agent Workshop! This guide will help you set up your environment and prepare for the workshop.

## Prerequisites

1. **Anaconda**: Ensure you have Anaconda installed on your machine. If not, download and install it from [here](https://www.anaconda.com/products/distribution).

2. **Jupyter Notebook**: This workshop requires Jupyter Notebook to be installed. Jupyter comes pre-installed with Anaconda.

## Environment Setup

1. **Create a Conda Environment**:
    ```bash
    conda create -n sales_agent_env python=3.8
    conda activate sales_agent_env
    ```

2. **Install Dependencies**:
    Run the following commands to install the necessary libraries within your conda environment:
    ```bash
    conda install -c conda-forge langchain
    conda install -c conda-forge langchain-community
    conda install -c conda-forge langchain_openai
    conda install -c conda-forge langchain-chroma
    conda install -c conda-forge litellm
    ```

## Workshop Preparation

1. **Clone the Workshop Repository**:
    ```bash
    git clone <repository-url>
    cd <repository-url>
    ```

2. **Open Jupyter Notebook**:
    ```bash
    jupyter notebook
    ```

3. **Navigate to the Notebook**:
    Open the `sales_agent_with_context.ipynb` file in Jupyter Notebook.

## Notebook Overview

The notebook is structured as follows:

1. **Imports and Setup**:
    - Essential libraries are imported.
    - Configurations for the LangChain framework are set up.

2. **Sales Agent Class Definition**:
    - A custom `SalesGPT` class is defined to control the sales agent’s behavior.

3. **Stages of Conversation**:
    - The sales process is broken down into various stages:
        1. Introduction
        2. Qualification
        3. Value Proposition
        4. Objection Handling
        5. Closing

4. **Running the Sales Agent**:
    - Example interactions with the sales agent are demonstrated.

## Key Concepts

- **LangChain**: A framework for developing applications powered by large language models (LLMs).
- **Sales Agent Model**: A conversational AI model designed to simulate a sales process.
- **Stages of Conversation**: Different phases of a sales interaction, each requiring specific handling.

## Additional Resources

- [LangChain Documentation](https://langchain.com/docs/)
- [Anaconda Documentation](https://docs.anaconda.com/)
- [Jupyter Notebook Documentation](https://jupyter.org/documentation)

## Troubleshooting

- Ensure that you are using the correct conda environment by running `conda activate sales_agent_env`.
- Verify that all dependencies are installed without errors.
- If Jupyter Notebook does not start, check your Anaconda installation and PATH variables.

By following this guide, you should be well-prepared for the workshop. If you have any questions or run into issues, please reach out to the workshop facilitator.
