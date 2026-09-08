# Hi there, I'm Irtaz Irfan 👋

**AI Systems & Machine Learning Engineer**  
Specialized in parameter-efficient model alignment, high-throughput LLM serving infrastructure, generative computer vision, high-dimensional vector search, and real-time distributed spatial backends.

---

### 🛠 Technical Stack & Tooling

**Languages & Core Frameworks:**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)

**Generative AI, PEFT & Retrieval:**  
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)
![PEFT](https://img.shields.io/badge/PEFT%20%2F%20LoRA-FF6F00?style=flat&logo=google&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6600?style=flat&logo=databricks&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Mermaid.js](https://img.shields.io/badge/Mermaid.js-FF3670?style=flat&logo=mermaid&logoColor=white)

**Systems, Databases & Infrastructure:**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![PostGIS](https://img.shields.io/badge/PostGIS-006400?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Uvicorn](https://img.shields.io/badge/Uvicorn-499848?style=flat&logo=gunicorn&logoColor=white)

---

### 🚀 Flagship Core Architectures

| Repository | Domain | Key Architecture / Technical Metric | Status |
| :--- | :--- | :--- | :--- |
| **[vlm-spatial-eval](https://github.com/irtazirfan08-source/vlm-spatial-eval)** | VLM Post-Training & Eval | PEFT/LoRA ($r=8$) spatial alignment; **+8.3% accuracy gain** under noise degradation | CI Passing (12 Tests) |
| **[PagedInfer](https://github.com/irtazirfan08-source/PagedInfer)** | ML Systems & LLM Serving | Paged KV-cache memory virtualization; eliminated internal memory fragmentation | Production Core |
| **[Dual-Attention-GAN-LLIE](https://github.com/irtazirfan08-source/Dual-Attention-GAN-LLIE)** | Generative Image Restoration | Dual spatial/channel attention GAN on LoLI-Street; quantitative PSNR/SSIM evaluation | Benchmark Ready |
| **[VectorCore](https://github.com/irtazirfan08-source/VectorCore)** | Information Retrieval & Search | Custom Approximate Nearest Neighbor (ANN) index; sub-2ms high-dimensional vector search | Optimized |
| **[MCP-Mesh](https://github.com/irtazirfan08-source/MCP-Mesh)** | Distributed Agent Protocols | Model Context Protocol gateway with automated discovery & bidirectional schema routing | Microservice Mesh |
| **[CTG_Shield_Spatial_Engine](https://github.com/irtazirfan08-source/CTG_Shield_Spatial_Engine)** | Geospatial Risk & Streaming | PostGIS polygonal queries (`ST_Contains`, `ST_DWithin`) with sub-second WebSocket SOS dispatch | Live Backend |

---

### 🔬 Flagship Deep Dives

1. **[vlm-spatial-eval — Spatial Robustness Benchmark & LoRA Alignment for VLMs](https://github.com/irtazirfan08-source/vlm-spatial-eval)**
   * **Domain:** Multimodal Alignment, Vision-Language Robustness & Parameter-Efficient Fine-Tuning (PEFT)
   * **Capabilities & Metrics:** Diagnosed architectural degradation modes across CLIP, SigLIP, and SmolVLM under photometric noise. Engineered a conversational synthetic instruction dataset and trained low-rank adapters (`q_proj`, `v_proj`, $r=8$, 0.29% trainable params) with prompt loss-masking. Achieved an **+8.3% absolute accuracy gain** on balanced relational discrimination without catastrophic forgetting on open-domain visual tasks.

2. **[PagedInfer — High-Throughput Paged KV-Cache LLM Serving Engine](https://github.com/irtazirfan08-source/PagedInfer)**
   * **Domain:** ML Systems Engineering, Memory Virtualization & Autoregressive Inference
   * **Capabilities & Metrics:** Implemented non-contiguous virtual memory block allocation for LLM key-value caches, eliminating GPU/CPU memory fragmentation. Features continuous dynamic request batching, prefill/decode phase separation, and asynchronous streaming generation for high-concurrency client workloads.

3. **[Dual-Attention-GAN-LLIE — Generative Low-Light Image Restoration](https://github.com/irtazirfan08-source/Dual-Attention-GAN-LLIE)**
   * **Domain:** Deep Learning Vision Research, Generative Adversarial Networks & Restoration
   * **Capabilities & Metrics:** Architected a custom U-Net generator featuring interleaved spatial and channel-wise attention mechanisms paired with a relativistic discriminator. Evaluated on the LoLI-Street benchmark dataset with rigorous quantitative validation across PSNR, SSIM, and perceptual LPIPS metrics.

4. **[VectorCore — High-Performance Vector Index & ANN Search Engine](https://github.com/irtazirfan08-source/VectorCore)**
   * **Domain:** Information Retrieval, High-Dimensional Vector Geometry & Embeddings
   * **Capabilities & Metrics:** Built a lightweight Approximate Nearest Neighbor (ANN) indexing system implementing optimized Cosine, Euclidean, and Dot-Product distance metrics. Delivers sub-2ms query latency with deterministic Recall@K across high-dimensional multimodal embedding distributions.

5. **[MCP-Mesh — Distributed Agent Gateway & Model Context Protocol Mesh](https://github.com/irtazirfan08-source/MCP-Mesh)**
   * **Domain:** Agentic Systems, Tool Orchestration & Microservice Interoperability
   * **Capabilities & Metrics:** Centralized agent-to-tool integration mesh built on the Model Context Protocol (MCP). Implements dynamic tool discovery, bidirectional JSON-RPC schema validation, process isolation, and fault-tolerant agent execution graphs.

6. **[CTG_Shield_Spatial_Engine — Geospatial Risk Telemetry & Emergency SOS Dispatch](https://github.com/irtazirfan08-source/CTG_Shield_Spatial_Engine)**
   * **Domain:** Geospatial Intelligence, Spatial Databases & Real-Time Telemetry
   * **Capabilities & Metrics:** Engineered an asynchronous FastAPI spatial telemetry engine backed by PostGIS spatial indexing (`ST_Contains`, `ST_DWithin`) for real-time hazard polygon intersections. Delivers sub-second emergency WebSocket broadcasts synchronized with the cross-platform native client (**[CTG_Shield_Mobile](https://github.com/irtazirfan08-source/CTG_Shield_Mobile)**).

---

### ⚡ Developer Copilots & Applied AI Systems

| Project | Domain & Architecture | Core Stack | Repository |
| :--- | :--- | :--- | :--- |
| **ArchLens AI** | System Design Audit & Topology Synthesis | FastAPI • OpenCV • React • Mermaid.js | [View Code](https://github.com/irtazirfan08-source/archlens-ai) |
| **IncidentPulse AI** | SRE Root-Cause & Telemetry Diagnostics | FastAPI • SciPy EMD • React • Vite | [View Code](https://github.com/irtazirfan08-source/incidentpulse-ai) |
| **DocuAssist** | Grounded Enterprise Support RAG Engine | FastAPI • Scikit-Learn • React • Vector Search | [View Code](https://github.com/irtazirfan08-source/docuassist-ai) |
| **Football Vision** | Real-Time Multi-Object Tracking & Pitch Heatmaps | PyTorch • YOLO • ByteTrack • OpenCV | [View Code](https://github.com/irtazirfan08-source/football-vision-engine) |
| **RepoScope** | Codebase Cartography & AST Layer Blueprinting | FastAPI • AST Parser • React • Mermaid.js | [View Code](https://github.com/irtazirfan08-source/reposcope) |
| **SyncPilot** | Audio Diarization & Jira Action-Item Synthesizer | FastAPI • Diarization Engine • React | [View Code](https://github.com/irtazirfan08-source/syncpilot) |
| **Vocalis** | Duplex Real-Time Voice Virtual Assistant | FastAPI • Web Speech API • Harmonic WAV | [View Code](https://github.com/irtazirfan08-source/vocalis-ai) |
| **EvalIQ** | AI Mock Technical Interview Coach & Rubric Scorer | FastAPI • Speech Recognition • Rubric Scoring | [View Code](https://github.com/irtazirfan08-source/evaliq-ai) |

---

### 📊 GitHub Activity & Streak

<div align="center">
  <img src="https://streak-stats.demolab.com?user=irtazirfan08-source&theme=tokyonight&hide_border=true&timezone=Asia%2FDhaka" alt="GitHub Streak" height="195" />
</div>
