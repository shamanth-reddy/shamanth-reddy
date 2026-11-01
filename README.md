# Hi, I'm Shamanth 👋

**AI Engineer** focused on building practical LLM applications: retrieval-augmented generation, agents, and evaluation.

## What I work on
- Building LLM-powered apps (RAG pipelines, tool-using agents)
- Evaluating and improving model and retrieval quality
- Shipping ML services with clean APIs and reproducible setups

## Tech stack
- **Languages:** Python, SQL, TypeScript
- **Agentic AI & GenAI:** LangGraph, Semantic Kernel, LangChain, LlamaIndex, Model Context Protocol (MCP), multi-agent systems, tool calling, RAG (hybrid/semantic search, chunking), prompt engineering, LoRA fine-tuning, multimodal extraction
- **LLMs:** Anthropic Claude, OpenAI / Azure OpenAI, Llama 3
- **Evaluation & Safety:** RAGAS, ROUGE, BLEU, NeMo Guardrails, human-in-the-loop evaluation, PII/PHI masking, audit tracing
- **Data & Vector Search:** Milvus, Pinecone, Azure AI Search, PySpark, Pandas, AWS Glue, Pydantic
- **Cloud & MLOps:** AWS (SageMaker, Bedrock, EC2, S3), Azure AI Studio, Docker, Kubernetes, CI/CD, MLflow, OpenTelemetry, FastAPI, REST/gRPC
- **Classical ML:** XGBoost, Prophet, scikit-learn, Hugging Face Transformers

## Projects
All projects use public or synthetic data only.

- **[MiniMesh](https://github.com/shamanth-reddy/minimesh)**: a small stateful agent orchestrator built from scratch in Python (asyncio, Pydantic v2). It runs a Thought-Action-Observation loop with schema-validated tool calls, a state machine for error recovery, and context-window pruning. 
- **[Bank Onboarding Agent](https://github.com/shamanth-reddy/bank-onboarding-agent)**: a corporate KYC/onboarding reference implementation. A LangGraph workflow calls a custom MCP server over a mock banking backend, retrieves public AML/CDD regulations with RAG, applies guardrails and human review, and writes a cited risk memo with a full audit trail. Synthetic data only. 
- **[Clinical Policy RAG](https://github.com/shamanth-reddy/clinical-policy-rag)**: a prior-authorization assistant over public coverage policies and synthetic clinical notes, with PHI masking, hybrid chunking and search, policy-cited letters, and an evaluation harness (Recall@K, RAGAS, ROUGE/BLEU). 
- **[Edge-Vision Driver Fatigue Monitor](https://github.com/shamanth-reddy/edge-vision-fatigue)**: a real-time drowsiness detector using YOLOv8-pose, OpenCV and ONNX Runtime, optimized for edge hardware.

## Get in touch
- 📧 shamanthr09@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/g-shamanth)
