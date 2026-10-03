# Travel Reimbursement Approval Agent

GenAI-based travel reimbursement approval agent developed for the HCL GenAI Developer/Architect technical assignment.

## Approach

- LangChain agent
- RAG using FAISS
- Policy retrieval
- OpenAI LLM
- Tool-based claim evaluation
- Deterministic policy guardrails
- Structured JSON output
- Minimal decision dashboard

## Tools

- Policy search
- Receipt completeness check
- Per-diem limit checker
- Timeliness checker
- Approval threshold checker

## Running the Notebook

1. Use Python 3.13.
2. Open `SunnyGoyal.ipynb` in Jupyter Notebook.
3. Run all cells.
4. Enter the OpenAI API key when prompted using `getpass`.

The API key is not stored in the notebook.
