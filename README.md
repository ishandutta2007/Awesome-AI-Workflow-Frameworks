# Awesome-AI-Workflow-Frameworks

## Top AI Workflow Frameworks Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Agent Orchestration, Pipeline Composition & Production LLM Applications*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Workflow Frameworks**. These tools provide the scaffolding, abstractions, and orchestration layers developers need to compose multi-step AI workflows—from simple chains to complex multi-agent systems with tool use, memory, and evaluation.



**Examples** include LangChain, LlamaIndex, Haystack, Semantic Kernel, Flowise, Langflow, AutoGen, CrewAI, Dify, and DSPy (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, workflow orchestration, and open LLM application development—ideal for AI engineers, platform teams, and developers seeking transparent, vendor-independent frameworks.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[LangSmith](https://smith.langchain.com/)**  

  LangChain's observability and evaluation platform with detailed tracing of every LLM call, chain execution, and agent step—showing inputs, outputs, latency, token usage, and cost. **Free Developer plan** (1 seat, 5k base traces/month), **Plus at $39/seat/month** (10k base traces, 1 free serverless deployment), Enterprise with self-hosted/hybrid options.



- **[LangFlow Cloud](https://www.langflow.org/)**  

  Managed version of the open-source Langflow visual framework. Drag-and-drop LLM workflow builder with API deployment and MCP server support.



- **[Flowise Cloud](https://flowiseai.com/)**  

  Managed version of the open-source Flowise drag-and-drop LLM app builder. Visual chatbot construction with RAG pipelines and API endpoints.



- **[Dify Cloud](https://dify.ai/)**  

  Managed version of the open-source Dify LLM app development platform. Features agentic workflows, RAG pipeline, model management, and observability.



- **[CrewAI Enterprise](https://www.crewai.com/)**  

  Managed version of the open-source CrewAI multi-agent framework. Features deployment, monitoring, and team collaboration for agent crews.



- **[AutoGen Studio](https://microsoft.github.io/autogen/)**  

  Microsoft's managed interface for the AutoGen multi-agent framework. Visual agent composition and conversation orchestration.



## Open-Source GitHub Projects



- **[LangChain](https://github.com/langchain-ai/langchain)**  

  **The most widely adopted framework for building LLM applications** (MIT). **`create_agent` provides a minimal, highly configurable agent harness**—compose exactly the agent your use case needs from model, tools, prompt, and middleware. Supports OpenAI, Anthropic, Google, OpenRouter, Fireworks, Baseten, and Ollama. **LangSmith for tracing, debugging, and evaluation**. **The de facto standard for LLM application development.**



- **[LlamaIndex](https://github.com/run-llama/llama_index)**  

  **The leading data framework for LLM applications** (MIT). Specializes in **RAG pipelines, document indexing, and retrieval**. Features data connectors, indexes, query engines, and agents. **The best choice when your primary need is connecting LLMs to private data.**



- **[Haystack (deepset)](https://github.com/deepset-ai/haystack)**  

  **Production-ready NLP framework** (Apache-2.0). Features **typed pipelines** for RAG, question answering, and semantic search. **Strong enterprise focus** with component-based architecture and extensive evaluation tools. **Recommended for production-grade typed RAG pipelines.**



- **[Griptape](https://github.com/griptape-ai/griptape)**  

  **The Python framework for AI workflows and pipelines with chain of thought reasoning, external tools, and memory** (Apache-2.0) . **The most modular and composable open-source workflow framework.** **Five core primitives**: **Agents** (LLMs + Tools + Tasks), **Pipelines** (sequential/parallel task orchestration), **Workflows** (DAG-based execution with custom control flow), **Tasks** (discrete units of work), and **Tools** (Python functions callable by LLMs) . **Key innovation**: **Structures** can run as a library or **deployed as scalable API endpoints**—built-in FastAPI-based API server with Swagger docs for serving workflows over HTTP . **Supports OpenAI, Anthropic, Cohere, Hugging Face, Ollama, LM Studio, and Amazon Bedrock** . **Drivers architecture** for different prompt formats (Anthropic, Cohere, Gemini, Groq, SageMaker) . **The best choice when you want typed, composable Python workflows with built-in API deployment.**



- **[Semantic Kernel (Microsoft)](https://github.com/microsoft/semantic-kernel)**  

  **Microsoft's LLM orchestration SDK** (MIT). Features planners, plugins, memories, and connectors for C#, Python, and Java. **Deep integration with Azure OpenAI and Microsoft ecosystem.** The foundation for Microsoft Copilot extensibility.



- **[AutoGen (Microsoft)](https://github.com/microsoft/autogen)**  

  **Multi-agent conversation framework** (MIT). **The most mature open-source multi-agent orchestration**—agents converse, execute code, and collaborate to solve tasks. Features group chat, nested chats, and human-in-the-loop. **50,000+ GitHub stars.**



- **[CrewAI](https://github.com/crewAIInc/crewAI)**  

  **Role-based multi-agent collaboration framework** (MIT). **The most accessible multi-agent framework**—define agents with roles, goals, and backstories, then compose crews with sequential or hierarchical processes. Features tools, memory, and delegation. **40,000+ GitHub stars.**



- **[Dify](https://github.com/langgenius/dify)**  

  **Open-source LLM app development platform** (Apache-2.0 with conditions). **157,000+ GitHub stars.** Features **agentic workflows**, **RAG pipeline**, **model management**, and **observability**. Visual workflow builder with API deployment. **The most complete open-source alternative to commercial LLMOps platforms.**



- **[DSPy (Stanford)](https://github.com/stanfordnlp/dspy)**  

  **Framework for programming—not prompting—LLMs** (MIT). **The most academically rigorous approach to LLM optimization**—separate specification from implementation, then let DSPy compile optimal prompts and weights. Features modules, signatures, and optimizers. **Used in production at Databricks and other enterprises.**



- **[Flowise](https://github.com/FlowiseAI/Flowise)**  

  **Drag-and-drop LLM app builder** (Apache-2.0). **30,000+ GitHub stars.** Visual chatbot construction with RAG pipelines, API endpoints, and multi-model support. **The most accessible no-code LLM application builder.**



- **[Langflow](https://github.com/langflow-ai/langflow)**  

  **Visual framework for building multi-agent and RAG applications** (MIT). **100,000+ GitHub stars.** Drag-and-drop LLM workflow builder with API deployment and MCP server support. **The most widely adopted visual LLM development tool.**



### Additional Strong Open-Source Options



- **[Vercel AI SDK](https://github.com/vercel/ai)** — TypeScript toolkit for building AI applications with multi-provider support (OpenAI, Anthropic, Google, Mistral, Llama). **The standard for building custom AI interfaces in Next.js and React.**

- **[Pydantic AI](https://github.com/pydantic/pydantic-ai)** — Agent framework from the Pydantic team. **Type-safe agent development** with structured outputs and dependency injection.

- **[Agno (formerly Phidata)](https://github.com/agno-agi/agno)** — Full-stack framework for building multi-modal agents with memory, knowledge, and tools. **Lightweight and performant** with 10,000+ GitHub stars.

- **[Smolagents (Hugging Face)](https://github.com/huggingface/smolagents)** — Minimal agent framework that writes Python code to call tools. **The simplest approach to code-writing agents** from Hugging Face.

- **[Swarm (OpenAI)](https://github.com/openai/swarm)** — Lightweight multi-agent orchestration from OpenAI. **Educational and experimental**—demonstrates handoffs and routines.

- **[Letta (formerly MemGPT)](https://github.com/letta-ai/letta)** — Stateful agents with long-term memory. **The most sophisticated open-source memory architecture for agents.**

- **[MetaGPT](https://github.com/geekan/MetaGPT)** — Multi-agent framework that assigns software company roles (PM, architect, engineer). **The most structured approach to multi-agent software development.**

- **[n8n](https://github.com/n8n-io/n8n)** — Open-source workflow automation with AI capabilities (Sustainable Use License). **400+ integrations, LangChain nodes, and custom code execution.**

- Community **n8n** workflows for AI workflow orchestration and agent deployment automation.



**Frameworks for building custom systems**: Combine **Griptape** for typed Python workflows with built-in API deployment, **LangChain** for agent orchestration, **LlamaIndex** for RAG pipelines, **CrewAI** or **AutoGen** for multi-agent collaboration, **Dify** for visual workflow building, and **DSPy** for prompt optimization—creating a comprehensive AI workflow stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- AI workflow frameworks handling LLM applications must comply with data protection regulations (GDPR, CCPA, etc.) and model provider terms of service.

- **Framework selection depends on primary use case.** Griptape for typed Python workflows with built-in API deployment, LangChain for general agent orchestration, LlamaIndex for RAG and data indexing, CrewAI for accessible multi-agent collaboration, AutoGen for mature multi-agent conversation, Dify for visual development, DSPy for prompt optimization. **No single framework dominates across all use cases.**

- **Griptape's deployment story is the differentiator.** Structures can run as a library or **deployed as scalable API endpoints** with FastAPI, Swagger docs, and optional hosted cloud—**most workflow frameworks require you to build the API layer yourself** .

- **Self-hosted open-source solutions require proper security hardening, LLM infrastructure (or API keys), and ongoing maintenance.** AI workflow frameworks evolve rapidly—pin versions and test upgrades before production deployment.



---



**Made for AI engineers, platform teams, and developers building transparent AI workflow solutions.**  

Let's make AI Workflow Frameworks more open, data-driven, and production-ready.
