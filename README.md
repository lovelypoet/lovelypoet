# 👋 Hello there! Bonjour mon ami!

I'm **Duc Anh Nguyen (David)** — a AI engineer from Vietnam 🇻🇳

🎓 **B.Eng in Information and Communication Technology @ USTH**

🤖 **Machine Learning | Deep Learning | Computer Vision | Edge AI**

I have **1+ year of hands-on experience** building AI systems through university research, engineering competitions, and product-oriented development.

I've always been fascinated by one question:

**How do you take a model that works in a notebook and make it actually work in the real world?**

That question has shaped my engineering journey:

- 🔬 **Machine Learning Research:** Developed and optimized deep learning models for PCB defect classification, achieving a **93.3% model size reduction** and approximately **22.5× faster inference**.
- 🦾 **AI Product Development:** Built V-Hand, a wearable sign language recognition system, combining sensor fusion, time-series modeling, and embedded AI.
- 🏭 **Industrial AI:** Worked with AOI inspection systems at Foxconn, gaining hands-on exposure to PCB defect detection in a real manufacturing environment.
- 💻 **Software Engineering:** Gained professional experience at AvePoint, contributing to C#/.NET backend development, REST APIs, application services, and database integration.

**My engineering philosophy:** I don't just want to build models that achieve good metrics. I want to understand the entire pipeline — from data processing and model development to optimization, integration, and deployment.

📫 **Contact:** [ducanh3105.work@gmail.com](mailto:ducanh3105.work@gmail.com)

---

## 🔭 Featured Research & Projects

### 🎓 1. Knowledge Distillation for Edge Device in PCB Defect Classification
*Undergraduate Thesis | Computer Vision & Edge AI*

**Goal:** Compress and optimize a deep learning model for PCB defect classification, enabling efficient inference on resource-constrained devices.

- **Tech Stack:** Python, PyTorch, TensorFlow/Keras, CNN, Knowledge Distillation, TensorFlow Lite, INT8 Quantization, NNAPI, Grad-CAM.
- **Approach:** Applied Knowledge Distillation to transfer knowledge from a larger teacher model into a lightweight student model, followed by quantization and deployment optimization.
- **Results:**
  - 📦 **93.3% smaller model:** 52.86 MB → 3.52 MB.
  - ⚡ **~22.5× faster inference** compared with the original baseline.
  - 🎯 **86.2% accuracy**, CV-verified, achieving a +7.4 percentage-point improvement over the no-KD baseline.
- **Focus:** Model compression, inference optimization, and practical Edge AI deployment.

### 🥇 2. V-Hand 2.0 — Smart Sign Language Recognition Glove
*[SilentVoix](https://github.com/lovelypoet/SilentVoix) | 1st Prize, APEC Innovation National Competition 2026*

**Goal:** Develop an intelligent wearable system that enables two-way communication between sign language users and non-signers.

- **Tech Stack:** Python, PyTorch, LSTM, ESP32-S3, MPU-6050, Flex Sensors, Sensor Fusion, Embedded AI.
- **Approach:** Combined IMU and flex sensor data to capture hand movements and recognize sign language gestures using time-series modeling.
- **Implementation:** Developed the embedded hardware, sensor data acquisition pipeline, gesture recognition model, and real-time inference workflow.
- **Status:** Developed iteratively since May 2025, progressing from an early prototype toward a functional wearable AI product.
- **Achievement:** 🥇 First Prize at APEC Innovation National Competition 2026.

### 🌉 3. VBridge — Real-time VI↔EN Speech Translator
*Vietnam AI Innovation Challenge 2026*

**Goal:** Build a real-time, on-device speech translation system for multilingual business communication.

- **Tech Stack:** C++, Python, PyTorch, TensorFlow/Keras, Whisper.cpp, NLLB-600M, ONNX Runtime, INT8 Quantization.
- **Pipeline:** Voice Activity Detection (VAD) → Automatic Speech Recognition (ASR) → Machine Translation (MT) → Text-to-Speech (TTS).
- **Approach:** Applied sequence-level Knowledge Distillation and quantization to optimize the NLLB-600M translation model.
- **Result:** Compressed the translation model to approximately 1.8 GB.
- **Focus:** Multimodal AI pipelines, model optimization, and on-device inference.

---

## 💼 Professional Experience

### 💻 Junior AI Engineer — AvePoint
*Oct – Nov 2026*

- Contributed to backend development using **C# and ASP.NET Core**.
- Developed REST API endpoints and application services for an Attendance Management system.
- Worked with a layered architecture: **API → Service → Repository → Database**.
- Integrated database operations using SQL Server and implemented JWT-based authentication.
- Contributed to chatbot backend development, focusing on API endpoints and service-layer logic.

### 🏭 AOI Engineer — Foxconn Industrial Internet Company
*Internship | Apr – Jul 2026*

- Worked with Automated Optical Inspection (AOI) systems in a PCB manufacturing environment.
- Fine-tuned machine learning models for PCB defect inspection on production AOI machines.
- Gained practical exposure to industrial inspection workflows, PCB defect identification, and hardware troubleshooting.
- Developed an understanding of real-world challenges in deploying and maintaining ML-based inspection systems.
- This experience inspired my undergraduate thesis on Knowledge Distillation and model compression for resource-constrained devices.

---

## 🧪 Additional Projects & Exploration

I enjoy exploring different areas of AI beyond my core research interests. Some projects that have helped me expand my engineering perspective:

- 🧠 [CVMultimodal — Vision and Language Fusion Framework](https://github.com/lystiger/CVMultimodal): Exploring multimodal learning and vision-language fusion.
- 🤖 [CareerOS — Multi-Agent Career Assistant](https://github.com/lovelypoet/Multi-Agent_CareerOS-): Exploring multi-agent architectures, LLM applications, and automated job discovery workflows.
- 📚 [Paper Reader Agent](https://github.com/lovelypoet/PAPER-READER-AGENT): An AI agent for research paper and document understanding.

These projects reflect my curiosity about how machine learning, language models, and software engineering can work together to solve practical problems.

---

## 🛠️ Technical Arsenal

**Programming Languages**
- Python, C/C++, C#, SQL

**Machine Learning & Deep Learning**
- PyTorch, TensorFlow/Keras, Scikit-learn
- CNN, LSTM, Transformers
- Computer Vision, NLP, Time-series Modeling
- NumPy, Pandas

**Model Optimization & Edge AI**
- Knowledge Distillation
- INT8 / Float32 Quantization
- Model Compression
- TensorFlow Lite, ONNX, ONNX Runtime, NNAPI

**LLM & AI Engineering**
- Large Language Models (LLMs)
- Retrieval-Augmented Generation (RAG)
- LangGraph, AI Agents
- Embedding Models, Vector Databases

**Backend & Database**
- ASP.NET Core, FastAPI
- REST API Development
- PostgreSQL, SQL Server, pgvector, ChromaDB

**Embedded Systems & Hardware**
- ESP32 / ESP32-S3, Arduino, Raspberry Pi
- IMU, Flex Sensors, Sensor Fusion
- Real-time Data Acquisition and Processing

**Development Tools & Infrastructure**
- Git, GitHub, Bash, Linux
- Docker, CUDA, VS Code, Jupyter Notebook

---

## 🏆 Awards & Achievements

- 🥇 **1st Prize** — APEC Innovation National Competition 2026.
- 🥉 **3rd Prize** — USTH Scientific Research Competition 2026.
- 🏅 **Consolation Prize** — USTH Scientific Research Competition 2025.
- 🏅 **3rd Prize** — USTH Innovation Competition 2026.
- 🎖️ **Top 20 Teams** — TechXpro Challenge 2025, by VinTech.
- 📊 **Academic Excellence:** A grades in Computer Vision, Machine Learning, Deep Learning, NLP, and OOSAD; A+ in Computer Graphics.

---

## 🎓 Education

**University of Science and Technology of Hanoi (USTH)**

Bachelor of Engineering in Information and Communication Technology (ICT)

- Focus areas: Machine Learning, Deep Learning, Computer Vision, Natural Language Processing.
- Undergraduate thesis: Knowledge Distillation for Edge Device in PCB Defect Classification.

---

## 🗣️ Languages

- 🇻🇳 Vietnamese — Native
- 🇬🇧 English — IELTS 6.5
- 🇫🇷 French — A2 (*Un petit peu !*)

---

## 🌱 Currently Exploring

- Deep Learning architectures and modern Transformer-based models.
- Machine Learning fundamentals, model evaluation, and data-centric AI.
- LLM applications, RAG systems, and AI Agent architectures.
- End-to-end ML engineering: from data pipelines and model training to production deployment.
- Efficient inference and model optimization on resource-constrained devices.

---

### 🤝 Let's Connect!

I'm always open to discussing Machine Learning, Deep Learning, Computer Vision, Edge AI, and interesting engineering projects.

If you're working on something exciting or looking for a passionate ML Engineer to collaborate with, feel free to reach out!

📧 **Email:** [ducanh3105.work@gmail.com](mailto:ducanh3105.work@gmail.com)

🌐 **GitHub:** [@lovelypoet](https://github.com/lovelypoet)

**"Build things that work, understand why they work, and make them work better."** 🚀
