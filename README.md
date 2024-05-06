# Chat with PDFs
This is a project to deal with RAG process chatting with PDFs, using open-source models. All content of the project is in a colab notebook. For this project I am using Large Language Model (LLM) Ollama. So, to start, install Ollama for Linux (Google machines use linux):

`!curl -fsSL https://ollama.com/install.sh | sh`

Or to install the others OS [download ollama](https://ollama.com/download).

After install Ollama on colab notebook you can use a terminal to run Ollama model. As an example, you can use:

`ollama serve & ollama run MODEL`

The MODEL can be `llama2:7b`, `llama2:13b`, `llama3:8b`, `gemma:7b` and so on. You can find all models and instructions [here](https://ollama.com/library). 

After this you can instantiate the model and do all the steps exposed on the notebook.

*Note: There are no PDFs in this repository to be used*
