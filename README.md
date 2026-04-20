<div align="center">

# James Lenhard

**Computer Science & Economics, William & Mary Class of 2029**

[GitHub](https://github.com/jameslovespancakes) · [jmlenhard@wm.edu](mailto:jmlenhard@wm.edu)

</div>

---

## About

I am a Computer Science and Economics student at William & Mary with a strong interest in algorithmic trading, machine learning, and quantitative research. I enjoy working at the intersection of markets and modeling, applying techniques from statistical learning, time-series analysis, and systematic strategy design to real financial data. Beyond quantitative work, I build practical ML systems across domains such as healthcare diagnostics, educational technology, and developer tooling.

## Featured Projects

### AI and Machine Learning

#### [DermaAI](https://github.com/jameslovespancakes/technica-2025)
*AI-Powered Skin Condition Classification — Technica 2025 Hackathon*

A full-stack web application that classifies user-submitted images of skin conditions and generates detailed, AI-driven explanations of the results.

**Key Features**
- SwinV2 Tiny transformer model trained on 216 skin condition categories
- Test-time augmentation for improved accuracy and reliability
- Automated explanations via the Gemini 2.0 Flash API
- Interactive follow-up chat with persistent conversation context

**Tech Stack:** Flask, PyTorch, React 18, Vite, TailwindCSS, Three.js, Gemini API

---

#### [Astraea](https://github.com/jameslovespancakes/Astraea)
*AI-Powered Educational Game Generator*

A platform that enables educators to create custom HTML5 educational games from natural language prompts, removing the need for programming experience.

**Key Features**
- Multi-model AI pipeline (Falcon-7B, BLIP-2, Gemini 1.5)
- Real-time leaderboards and teacher dashboards
- Instant game preview with integrated student progress tracking

**Tech Stack:** Flask, PyTorch, Next.js 14, TailwindCSS, Phaser 3, Socket.io

---

### Model Context Protocol (MCP) Servers

A collection of specialized MCP servers that extend language model capabilities by connecting them to external data sources and services. Each server implements the Model Context Protocol to support secure, standardized interactions between AI applications and real-world systems.

All servers are published as PyPI modules. [View PyPI profile](https://pypi.org/user/idk_james/)

#### [MokuPDF](https://github.com/jameslovespancakes/mokupdf)
*Intelligent PDF Processing Server*

A server that allows AI tools such as Claude Desktop to read and process PDF files, supporting both digital and scanned documents through OCR.

**Key Features**
- Tesseract-based OCR for scanned documents
- Fuzzy search across local directories
- Embedded image extraction from PDFs
- JSON-RPC communication protocol

**Tech Stack:** Python 3.8+, Tesseract OCR, JSON-RPC, MCP

#### [Memory-MCP (Hippocampus)](https://github.com/jameslovespancakes/Memory-MCP)
*Persistent Memory Server for Language Models*

A memory system modeled on biological processes that enables AI assistants to retain information across conversation sessions through semantic storage and retrieval.

**Key Features**
- Semantic similarity search using FAISS vector indexing
- Memory consolidation and decay algorithms
- Local-first storage with no external API dependency
- Rate limiting and access controls

**Tech Stack:** Python 3.9+, Sentence Transformers, FAISS, JSON

#### [BinanceUS-MCP](https://github.com/jameslovespancakes/BinanceUS-mcp)
*Cryptocurrency Trading Integration*

An MCP-compliant server that connects AI assistants to the Binance US platform for market data retrieval and trading operations.

**Key Features**
- Real-time market data access
- Programmatic trading operations
- Secure API authentication
- MCP-compliant architecture

**Tech Stack:** Python, Binance US API, MCP

---

## Open Source Contributions

### TensorFlow
Contributions to one of the most widely used machine learning frameworks.

- [#102674](https://github.com/tensorflow/tensorflow/pull/102674) — Fix TensorFlow Lite build error with Android NDK. Added platform-specific guards to resolve compilation errors on Windows and Android NDK configurations.
- [#102663](https://github.com/tensorflow/tensorflow/pull/102663) — Fix TypeError when serializing `tf.nn.log_softmax` activation. Resolved a Keras model deserialization issue affecting `log_softmax` activation functions.

### Sanic
Contributions to the high-performance Python web framework.

- [#3086](https://github.com/sanic-org/sanic/pull/3086) — Fix race condition in worker restart causing spawn failure. Resolved a race condition that prevented workers from restarting reliably.
- [#3085](https://github.com/sanic-org/sanic/pull/3085) — Fix AttributeError in `close_if_idle()` when `_http` is not initialized. Corrected a server shutdown crash through safer property access for uninitialized connections.

---

## Technical Skills

**Languages:** Python, JavaScript, TypeScript

**Frameworks and Libraries:** Next.js, Flask, PyTorch, React

**Tools and Platforms:** Git, Cloudflare, Gemini API

**Areas of Focus**
- AI/ML integration and the Model Context Protocol
- Full-stack web development
- Educational technology
- PDF processing and OCR
- Real-time applications

---

## Current Focus

- Building AI-powered tools for productivity and education
- Developing Model Context Protocol integrations
- Designing full-stack applications with modern frameworks
- Pursuing interdisciplinary work in computer science and economics

---

## Contact

I welcome opportunities to collaborate on technical projects or discuss work at the intersection of technology and economics.

- Email: [jmlenhard@wm.edu](mailto:jmlenhard@wm.edu)
- GitHub: [@jameslovespancakes](https://github.com/jameslovespancakes)
