# IndexMind

A small project for learning retrieval-augmented generation (RAG): load documents, find relevant passages, and use them to answer questions.

Still in the early stages. Everything currently lives in [`rag-1.ipynb`](rag-1.ipynb).

## What's here

- Token counting and text embeddings
- Loading a web page and splitting it into chunks
- Similarity search with ChromaDB
- Answer generation with LangChain and OpenAI
- Tracing with LangSmith

The notebook uses a blog post about LLM agents as its sample document. The final RAG chain is still being worked on.

## Try it

You'll need Python, `uv`, a Jupyter environment, and API keys for OpenAI and LangSmith.

1. Open `rag-1.ipynb` in Jupyter or VS Code.
2. Run the package installation cell. You'll also need `numpy` and `langchain-classic`.
3. Set `OPENAI_API_KEY` and `LANGCHAIN_API_KEY` in your environment.
4. Run the notebook cells in order.

OpenAI calls use your API credits. Keep your keys out of the notebook before committing it.
