# README: Graph-Enhanced Retrieval-Augmented Generation (RAG) with ApertureDB and LangChain  

This project demonstrates a **Graph-Enhanced Retrieval-Augmented Generation (RAG)** system using **ApertureDB**, **LangChain**, and **OpenAI's GPT-4o**. The goal is to combine **vector search** with **graph-based retrieval** to enhance document retrieval and improve response quality.  

### **Key Features**  

1. **Data Ingestion & Vectorization**:  
   - Articles are converted into **LangChain Documents** and stored in **ApertureDB**.  
   - OpenAI embeddings power the vector search.  

2. **Graph-Based Retrieval (Multi-Hop RAG)**:  
   - Articles are linked using **entity relationships** in **ApertureDB**.  
   - A multi-hop retrieval method fetches **connected** articles for better context.  

3. **Vanilla RAG vs. Graph RAG**:  
   - **Vanilla RAG** retrieves documents using a standard similarity search.  
   - **Graph RAG** enhances retrieval by **tracing connections** between related articles.  

4. **Querying with OpenAI GPT-4o**:  
   - Context is passed to OpenAI’s API to generate responses based on retrieved articles.  

This approach improves the **depth** and **relevance** of responses by leveraging structured relationships between documents. Ideal for **news summarization, knowledge graphs, and advanced document retrieval.**
