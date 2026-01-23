# Towards Accurate AI-Driven ItihashQA: A Conversational Question Answering System Applied in Bangladeshi Historical Context

* The code is the official implementation of the work "Towards Accurate AI-Driven ItihashQA: A Conversational Question Answering System Applied in Bangladeshi Historical Context".
* Authors of the work: Arabindo Das Himu, Md Shawmoon Azad, Raiyan Rahman, and Mohammed Rakibul Hasan

### Idea

The research introduces **ItihashQA**, a publicly available, conversational AI-driven retrieval question-answering system (QA) specifically trained on the historical context of Bangladesh.

*   **Goal**: To develop an LLM system that is both reliable and accurate for the sensitive topic of history, addressing challenges like hallucinations and misinformation faced by other Large Language Models (LLMs).
*   **Approach**: ItihashQA combines the open-source **Stable Vicuña LLM** with expert-verified historical datasets. It is built upon the **Retrieval-Augmented Generation (RAG)** approach. The system integrates the **E5 embedding model** with the Stable Vicuña LLM to generate precise and context-aware responses.
*   **Performance**: The system demonstrated high accuracy, achieving an overall accuracy of **92.00%** in extensive human assessments across easy, medium, and hard difficulty levels, outperforming models like ChatGPT and BARD.

### Dataset

*   **Corpus**: The domain-specific dataset focuses on the objective history of Bangladesh, primarily from **1947 to 1971**.
*   **Sources**: Data was compiled from verifiable and authentic sources, mostly collected from PDFs of official government publications.

### Technical Details

*   **LLM Used**: StableVicuna-13B, an open-source autoregressive language model.
*   **Vector Database**: Chroma Database.
*   **Code Repository**: [https://github.com/shawmoonazad/ItihashQA](https://github.com/shawmoonazad/ItihashQA).

### Contact Authors

*   Md Shawmoon Azad: shawmoonazad.azad@northsouth.edu
