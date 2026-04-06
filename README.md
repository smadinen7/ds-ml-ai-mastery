# 🧠 DS · ML · AI Mastery Curriculum

> A self-directed, zero-to-master learning repository.  
> Every folder = one topic. Every day, open the folder and drop in the resources you studied.

---

## 📌 How to Use This Repo

1. **Pick a topic** from the curriculum below (follow the phases in order, or jump to what you need).
2. **Go into the folder** — open `resources.md` and log the course / paper / video / article you used that day.
3. **Build in the companion repo** → `ds-ml-ai-projects` (separate repository for all projects).
4. **Track progress** by checking off topics as you complete them.

---

## 🗺️ Curriculum Map — 14 Phases, 100+ Topics

| Phase | Area | Topics |
|-------|------|--------|
| 00 | **Foundations** | Python, Math, SQL, Algorithms |
| 01 | **Data Science Core** | EDA, Feature Eng, Stats, Time Series |
| 02 | **Classical ML** | Regression → Boosting → Bayesian |
| 03 | **Deep Learning** | NN → CNN → RNN → Transformers → Diffusion |
| 04 | **NLP** | Text → Embeddings → QA → TTS |
| 05 | **Computer Vision** | Classification → Detection → VLMs |
| 06 | **Large Language Models** | Architecture → Fine-Tuning → Alignment |
| 07 | **Generative AI & RAG** | RAG → Vector DBs → LangChain → GraphRAG |
| 08 | **AI Agents** | Tool Use → LangGraph → CrewAI → MCP |
| 09 | **Reinforcement Learning** | Q-Learning → PPO → RLHF |
| 10 | **MLOps & Production** | Tracking → Pipelines → Serving → Monitoring |
| 11 | **Cloud & Distributed ML** | AWS · GCP · Azure · HuggingFace |
| 12 | **Specialized Topics** | XAI, Federated, Quantum, AI Safety |
| 13 | **Interview & Career** | System Design, Papers, Portfolio |

---

## 📂 Detailed Structure

### 📗 Phase 00 — Foundations
```
00_Foundations/
├── 00_Setup_and_Tools          # conda, venv, Jupyter, Colab, VS Code, Git
├── 01_Python_for_Data_Science  # NumPy, Pandas, Matplotlib, Seaborn, Plotly
├── 02_Linear_Algebra           # Vectors, matrices, eigenvalues, SVD
├── 03_Calculus_and_Optimization# Derivatives, gradients, chain rule, convexity
├── 04_Probability_and_Statistics# Distributions, Bayes, MLE, CLT, Hypothesis tests
├── 05_Information_Theory       # Entropy, KL divergence, mutual information
├── 06_SQL_and_Databases        # SQL, NoSQL, data warehousing
└── 07_Data_Structures_and_Algorithms # Big-O, trees, graphs, sorting for interviews
```

### 📘 Phase 01 — Data Science Core
```
01_Data_Science_Core/
├── 01_Data_Collection_and_Web_Scraping   # APIs, BeautifulSoup, Scrapy
├── 02_Data_Cleaning_and_Preprocessing    # Null handling, outliers, encoding
├── 03_Exploratory_Data_Analysis          # Pandas profiling, correlation, distributions
├── 04_Feature_Engineering                # Binning, interaction, target encoding
├── 05_Data_Visualization                 # Matplotlib, Seaborn, Plotly, Tableau
├── 06_Statistical_Inference_and_Hypothesis_Testing
├── 07_Experiment_Design_and_AB_Testing
├── 08_Time_Series_Analysis               # ARIMA, Prophet, statsmodels
└── 09_Big_Data_Tools_Spark_Dask          # PySpark, Dask, Polars
```

### 📙 Phase 02 — Classical Machine Learning
```
02_Classical_ML/
├── 01_ML_Fundamentals_and_Workflow       # Bias-variance, cross-validation, pipelines
├── 02_Linear_and_Logistic_Regression
├── 03_Decision_Trees_and_Random_Forests
├── 04_Support_Vector_Machines
├── 05_Gradient_Boosting_XGBoost_LightGBM_CatBoost
├── 06_Unsupervised_Learning_Clustering   # K-means, DBSCAN, GMM, hierarchical
├── 07_Dimensionality_Reduction_PCA_tSNE_UMAP
├── 08_Anomaly_Detection
├── 09_Recommendation_Systems            # Collaborative, content-based, matrix factorization
├── 10_Model_Evaluation_and_Metrics      # AUC, F1, NDCG, calibration
├── 11_Hyperparameter_Tuning             # Grid, random, Bayesian, Optuna
├── 12_Ensemble_Methods                  # Stacking, blending, voting
└── 13_Bayesian_Methods                  # Naive Bayes, Gaussian process, Bayesian opt
```

### 📕 Phase 03 — Deep Learning
```
03_Deep_Learning/
├── 01_Neural_Network_Fundamentals        # Perceptron, activations, layers
├── 02_Backpropagation_and_Optimization   # SGD, Adam, learning rate schedules
├── 03_Regularization_Techniques          # Dropout, batch norm, weight decay
├── 04_Convolutional_Neural_Networks_CNN  # LeNet → ResNet → EfficientNet
├── 05_Recurrent_Neural_Networks_RNN_LSTM_GRU
├── 06_Attention_Mechanisms               # Self-attention, multi-head attention
├── 07_Transformers_Architecture          # BERT, GPT, T5, ViT, CLIP
├── 08_Autoencoders_and_VAEs
├── 09_Generative_Adversarial_Networks_GANs # GAN, DCGAN, StyleGAN, CycleGAN
├── 10_Diffusion_Models                   # DDPM, Stable Diffusion, score matching
├── 11_Graph_Neural_Networks              # GCN, GAT, GraphSAGE, message passing
├── 12_PyTorch_Mastery                    # Autograd, datasets, training loops, Lightning
├── 13_TensorFlow_and_Keras
└── 14_Transfer_Learning_and_Fine_Tuning  # Feature extraction, full fine-tuning
```

### 📒 Phase 04 — Natural Language Processing
```
04_NLP/
├── 01_Text_Preprocessing_and_Tokenization # regex, spaCy, BPE, SentencePiece
├── 02_Classical_NLP_TFIDF_BOW
├── 03_Word_Embeddings_Word2Vec_GloVe_FastText
├── 04_Sequence_Models_for_NLP            # seq2seq, encoder-decoder
├── 05_Named_Entity_Recognition
├── 06_Sentiment_Analysis
├── 07_Text_Classification
├── 08_Machine_Translation
├── 09_Question_Answering
├── 10_Text_Summarization                 # Extractive vs abstractive
├── 11_Information_Retrieval_and_Search   # BM25, dense retrieval, DPR
└── 12_Speech_Recognition_and_TTS        # Whisper, Tacotron, WaveNet
```

### 🖼️ Phase 05 — Computer Vision
```
05_Computer_Vision/
├── 01_Image_Fundamentals_and_OpenCV
├── 02_Image_Classification               # CNN-based, ImageNet benchmarks
├── 03_Object_Detection_YOLO_RCNN         # YOLO v5/v8, Faster R-CNN, DETR
├── 04_Image_Segmentation                 # FCN, U-Net, Mask R-CNN, SAM
├── 05_Face_Recognition                   # Dlib, FaceNet, ArcFace
├── 06_Video_Understanding                # Optical flow, action recognition
├── 07_Vision_Transformers_ViT            # ViT, DeiT, Swin Transformer
├── 08_Multimodal_Vision_Language_Models  # CLIP, BLIP, LLaVA, GPT-4V
├── 09_3D_Vision_and_Point_Clouds         # NeRF, point cloud processing
└── 10_Generative_Image_Models_DALLE_SD   # DALL-E, Stable Diffusion, Midjourney API
```

### 🤖 Phase 06 — Large Language Models
```
06_Large_Language_Models/
├── 01_LLM_Architecture_and_Pretraining   # GPT, BERT, decoder-only, scaling laws
├── 02_Tokenization_and_Vocabulary        # BPE, WordPiece, tiktoken
├── 03_Prompt_Engineering                 # Zero-shot, few-shot, CoT, meta-prompting
├── 04_In_Context_Learning_and_Few_Shot
├── 05_Fine_Tuning_SFT                    # Supervised fine-tuning, instruction tuning
├── 06_RLHF_and_Alignment                 # Reward models, PPO, DPO, Constitutional AI
├── 07_Parameter_Efficient_FineTuning_LoRA_QLoRA # LoRA, QLoRA, Adapters, Prefix tuning
├── 08_Quantization_and_Compression       # GPTQ, AWQ, bitsandbytes, ONNX
├── 09_Evaluation_and_Benchmarking        # MMLU, HumanEval, BIG-Bench, Arena
├── 10_Open_Source_LLMs_LLaMA_Mistral_DeepSeek # LLaMA 3, Mistral, DeepSeek, Qwen
├── 11_LLM_APIs_OpenAI_Anthropic_Gemini   # API usage, structured outputs, batching
└── 12_Multimodal_LLMs                    # GPT-4o, Claude 3, Gemini 1.5, Llava
```

### 🔍 Phase 07 — Generative AI & RAG
```
07_Generative_AI_and_RAG/
├── 01_RAG_Fundamentals                   # Indexing, retrieval, generation pipeline
├── 02_Vector_Databases_Pinecone_Chroma_FAISS # pgvector, Weaviate, Qdrant
├── 03_Embeddings_and_Semantic_Search     # OpenAI, E5, BGE, Cohere embeddings
├── 04_Advanced_RAG_Techniques            # HyDE, re-ranking, RAPTOR, self-RAG
├── 05_LangChain_Framework                # Chains, memory, tools, LCEL
├── 06_LlamaIndex                         # Nodes, indexes, query engines
├── 07_RAG_Evaluation_RAGAS               # Faithfulness, relevancy, BLEU, ROUGE
└── 08_Knowledge_Graphs_and_GraphRAG      # Neo4j, Microsoft GraphRAG
```

### 🕵️ Phase 08 — AI Agents
```
08_AI_Agents/
├── 01_Agent_Fundamentals_and_Architecture # Perceive → Plan → Act loop
├── 02_Tool_Use_and_Function_Calling
├── 03_ReAct_and_Chain_of_Thought
├── 04_Memory_Systems_for_Agents           # Short-term, long-term, episodic
├── 05_LangGraph                           # Stateful graphs, nodes, edges
├── 06_CrewAI_Multi_Agent_Systems          # Roles, crews, task delegation
├── 07_AutoGen                             # Conversational multi-agent
├── 08_OpenAI_Agents_SDK
├── 09_Model_Context_Protocol_MCP          # MCP servers, tools, resources
├── 10_Agentic_RAG                         # RAG + agents for dynamic retrieval
├── 11_Planning_and_Reasoning_Agents       # Tree of Thoughts, MCTS, RLHF agents
└── 12_Browser_and_Computer_Use_Agents     # Playwright, Selenium, computer use
```

### 🎮 Phase 09 — Reinforcement Learning
```
09_Reinforcement_Learning/
├── 01_RL_Fundamentals_MDP                # States, actions, rewards, policies
├── 02_Q_Learning_and_SARSA
├── 03_Deep_Q_Networks_DQN
├── 04_Policy_Gradient_Methods            # REINFORCE, vanilla PG
├── 05_Actor_Critic_A2C_A3C
├── 06_Proximal_Policy_Optimization_PPO
├── 07_Model_Based_RL                     # Dyna, World Models, Dreamer
├── 08_Multi_Agent_RL                     # Cooperative, competitive, MARL
├── 09_RLHF_from_Scratch                  # Reward modeling, alignment pipeline
└── 10_RL_for_Games_OpenAI_Gym            # Gymnasium, MuJoCo, Atari
```

### ⚙️ Phase 10 — MLOps & Production
```
10_MLOps_and_Production/
├── 01_Git_and_Version_Control_for_ML
├── 02_Experiment_Tracking_MLflow_WandB
├── 03_Data_Versioning_DVC
├── 04_ML_Pipelines_Airflow_Prefect_Mage
├── 05_Model_Registry_and_Management
├── 06_Containerization_Docker
├── 07_Kubernetes_for_ML
├── 08_Model_Serving_FastAPI_TorchServe_BentoML
├── 09_Model_Monitoring_and_Drift_Detection # Evidently, NannyML, Grafana
├── 10_Feature_Stores                     # Feast, Tecton, Hopsworks
├── 11_CI_CD_for_ML                       # GitHub Actions, Jenkins, testing
└── 12_LLMOps                             # LangSmith, Helicone, prompt versioning
```

### ☁️ Phase 11 — Cloud & Distributed ML
```
11_Cloud_and_Distributed_ML/
├── 01_AWS_for_ML_SageMaker
├── 02_GCP_for_ML_Vertex_AI
├── 03_Azure_ML
├── 04_Distributed_Training_Strategies    # Data/model parallel, DeepSpeed, FSDP
├── 05_HuggingFace_Hub_and_Ecosystem      # Transformers, Datasets, Spaces, PEFT
└── 06_Serverless_ML_Deployment           # Lambda, Cloud Functions, Modal
```

### 🔬 Phase 12 — Specialized Topics
```
12_Specialized_Topics/
├── 01_Causal_Inference                   # DAGs, do-calculus, potential outcomes
├── 02_Survival_Analysis                  # Kaplan-Meier, Cox PH
├── 03_Federated_Learning                 # FedAvg, privacy-preserving ML
├── 04_Edge_AI_and_TinyML                 # TFLite, ONNX, pruning, quantization
├── 05_AI_Safety_and_Alignment            # Interpretability, red-teaming, robustness
├── 06_Explainability_XAI_SHAP_LIME
├── 07_Fairness_Privacy_and_Ethics        # Differential privacy, bias auditing
├── 08_Quantum_ML                         # PennyLane, quantum circuits for ML
├── 09_AI_for_Science_Biology_Chemistry   # AlphaFold, molecular ML, genomics
├── 10_Robotics_and_Embodied_AI           # ROS, sim-to-real, manipulation
└── 11_AI_System_Design                   # Scalable ML systems, architecture patterns
```

### 🎯 Phase 13 — Interview & Career
```
13_Interview_and_Career/
├── 01_ML_System_Design                   # Design a recommendation / search system
├── 02_Coding_Interview_DS_Algo           # LeetCode patterns for MLE interviews
├── 03_Statistics_and_Probability_Interview
├── 04_ML_Concepts_Interview              # Common ML Q&A, math derivations
├── 05_Case_Studies_and_Take_Homes
├── 06_Research_Paper_Reading_List        # Must-read papers by topic
└── 07_Portfolio_and_GitHub_Tips          # README templates, demo tips
```

---

## 📅 Suggested Pacing

| Phase | Suggested Time |
|-------|---------------|
| 00 Foundations | 4–6 weeks |
| 01 Data Science Core | 3–4 weeks |
| 02 Classical ML | 4–6 weeks |
| 03 Deep Learning | 6–8 weeks |
| 04 NLP | 4–5 weeks |
| 05 Computer Vision | 3–4 weeks |
| 06 LLMs | 4–6 weeks |
| 07 GenAI & RAG | 3–4 weeks |
| 08 AI Agents | 3–4 weeks |
| 09 Reinforcement Learning | 4–5 weeks |
| 10 MLOps & Production | 3–4 weeks |
| 11 Cloud & Distributed ML | 2–3 weeks |
| 12 Specialized Topics | ongoing |
| 13 Interview & Career | ongoing |

**Total mastery timeline: ~12–18 months** (studying 2–3 hours/day)

---

## 🧪 Companion Projects Repository

> All projects live in → **`ds-ml-ai-projects`** (separate repo)

Suggested project categories:
- `beginner/` — Titanic, Iris, MNIST, movie recommendations
- `intermediate/` — Churn prediction, NLP sentiment, object detection
- `advanced/` — Fine-tuned LLM, RAG chatbot, RL game agent, MLOps pipeline
- `capstone/` — Full end-to-end production AI system

---

## 📋 How to Log Resources (resources.md format)

Each `resources.md` follows this template:

```markdown
# Resources — [Topic Name]

## 📺 Videos / Courses
- [ ] [Course Name](url) — Platform, ~X hours

## 📖 Books / Papers
- [ ] [Book/Paper Title](url)

## 🔗 Articles / Blogs
- [ ] [Article Title](url) — Source

## 💻 Code / Notebooks
- [ ] [Repo/Notebook Name](url)

## 📝 My Notes
> Add your own notes, key takeaways, and insights here
```

---

*Started: 2026 | Goal: Master DS · ML · AI end-to-end*
