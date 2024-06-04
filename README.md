- Retrieval-Augmented-Generation `RAG` using `LangChain(LLM), OpenAI, API`
- Simple script to use ChatGPT on your own files.

  Installation
  - Install Langchain and other required packages.
```
pip install langchain openai chromadb tiktoken unstructured
```
- Use your own `OpenAI API key` in constants.py.
- Place your own data into `data/data.txt`

Example usage
- Test reading `data/data.txt` file.
```
/> python chatgpt.py "what is my car name"
Your car name is BMW.
```
- Test reading `data/info.pdf` file.
```
/> python chatgpt.py "summarize info.pdf"
```
