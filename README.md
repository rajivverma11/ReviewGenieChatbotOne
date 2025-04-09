Discover how to make Large Language Models (LLMs) highly effective for your business needs without the complexity of fine-tuning! This application implements a Retrieval-Augmented Generation (RAG) strategy to enrich user queries with relevant information. By feeding both the original question and the retrieved context to the LLM, we achieve more insightful and relevant answers.

This implementation utilizes:

OpenAI: For generating text embeddings and processing LLM prompts.
Langchain: For streamlined prompt engineering.
FAISS: For efficient vector storage and retrieval of embeddings generated from cleaned and combined title and description data from a CSV file.
Gradio: To provide an intuitive and accessible interface for interacting with the question-answering chatbot.
