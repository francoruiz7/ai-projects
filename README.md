# AI Projects

Applied AI and LLM projects — prompt engineering, data extraction pipelines, and API integrations.

## Projects

### Email Data Extraction Pipeline
[`extraccion_datos_email.ipynb`](./extraccion_datos_email.ipynb)

A two-stage LLM pipeline that processes unstructured procurement emails and converts them into structured, actionable data:
1. **Extraction** — parses free-text emails into structured JSON (sender, branch, amount, terms, warranty, contact)
2. **Evaluation** — automatically classifies each quote as *Convenient*, *Regular*, or *Not Convenient* based on business rules

Built with the OpenAI SDK connected to Groq's API (Llama 3.1), pandas for data handling, and structured prompt design for reliable JSON output.
