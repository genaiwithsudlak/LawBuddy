# LawBuddy — AI Legal Assistant (In Development)

**LawBuddy** is an AI-powered legal assistant designed to support both legal professionals and everyday users. By fine-tuning and supervising LLMs on Indian and international law datasets, LawBuddy provides **accurate, context-aware answers** to legal queries and retains knowledge for future interactions.

---

## Features

- **Supervised Fine-Tuned Model**: Trained on a wide range of laws, legal documents, and case studies.
- **Persistent Knowledge Base**: Stores embeddings and conversation history so the model can answer follow-up questions more accurately.
- **Legal QA Module**: Provides precise answers to law-related questions for both professionals and laypersons.
- **Document Analysis**: Analyzes legal documents, contracts, and statutes to extract key insights.
- **Context-Aware Guidance**: Offers recommendations considering the legal context and scenario.
- **User-Friendly**: Accessible to lawyers, students, and general public seeking legal guidance.

---

## Current Status

- **In Development**: Core modules, dataset preparation, and fine-tuning are ongoing.
- **Planned Improvements**:
  - Expanded legal knowledge base across Indian and international law.
  - Enhanced context understanding for multi-turn conversations.
  - Summarization and note-taking from legal documents.
  - Integration with OCR for scanned legal documents.
  - Persistent memory to improve accuracy over repeated interactions.

---

## Architecture (Proposed)

Legal Texts / Laws / Cases
↓
Data Preprocessing & OCR Correction (if scanned)
↓
Supervised Fine-Tuning on LLM
↓
LawBuddy AI Model
↓
Store Embeddings & Conversation History (Persistent Knowledge Base)
↓
Legal QA, Summarization, Notes & Guidance
↓
Interactive Responses for Users

yaml
Copy code

---

## Usage (Planned)

1. Upload legal documents or enter questions.
2. The system processes input and stores embeddings in the knowledge base.
3. Model generates concise answers, summaries, or notes.
4. Users can ask follow-up questions; model uses stored knowledge to provide better responses.

---

## Technology Stack

- **LLM Modules**: Fine-tuned transformers (mT5, Qwen, or similar) for legal domain.
- **Vector Embeddings**: Semantic search across laws, cases, and conversation history.
- **Persistent Memory**: Database for storing embeddings and conversation context.
- **OCR**: Optional module for scanned legal documents.
- **Python Libraries**: Transformers, LangChain, PyMuPDF, OCR tools.

---

## Requirements (Planned)

- Python 3.10+
- transformers
- torch
- sentence-transformers
- langchain
- PyMuPDF / pdfplumber
- OCR libraries (Tesseract, ByT5 dependencies)

---

## Future Roadmap

- Multi-jurisdiction legal knowledge support.
- Conversational legal assistant for interactive advice.
- Deployment as a web-based platform or API for public and professional use.
- Continuous learning from new legal documents and cases.

---

## Author

**Sudarshan Lakshate** – Developer & Maintainer

---

## License

MIT License
