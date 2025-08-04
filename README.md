## 🚀 Features

- ✅ **Structured JSON Output**  
  News summaries are consistently returned in a strict, machine-readable JSON format, making them easy to parse and analyze.

- ✅ **Few-shot Prompting**  
  Uses multiple examples to guide the LLM's response structure, ensuring outputs follow the intended format and tone.

- ✅ **Function Calling with Google Search**  
  Integrates real-time search by invoking Google Search as a tool, fetching the most recent and credible sources.

- ✅ **Agent-Based Architecture**  
  Implements a multi-turn, history-aware agent capable of contextual conversation and iterative refinement.

- ✅ **LLM-Based Response Evaluation**  
  Evaluates each news output based on fluency, accuracy, and completeness using rubric-driven, model-generated scores and rationale.

- ✅ **Grounded Responses with Citations**  
  Every answer includes references to real sources, ensuring transparency and enabling fact-checking.

---

## 🔄 Workflow

1. **User Input**  
   The user asks for news on a specific topic (e.g., "Latest AI developments in healthcare").

2. **Tool Invocation**  
   The agent uses function calling to trigger Google Search and retrieve relevant articles.

3. **Gemini Model Summarization**  
   The Gemini model digests the fetched content and returns a clean JSON summary of the most relevant headlines.

4. **Structured Output Display**  
   The JSON is parsed and displayed in a readable format with clickable sources and timestamps.

5. **Self-Evaluation (Optional)**  
   The response is evaluated on key metrics such as relevance and accuracy using LLM-based grading.

# news-bot
