# Hi there 👋, I'm Guy Vitelson

I'm a Full-Stack Developer and independent researcher with a strong academic foundation in Computer Science, passionate about exploring AI, computational biology, and theoretical computer science. My journey into computer science stems from a lifelong curiosity about programming, which I transitioned into full-time after a successful career in post-production.

I enjoy working on projects that blend **cutting-edge research** with **practical software engineering**, and I'm eager to collaborate, learn, and contribute to impactful interdisciplinary work.

---

# 🌟 Areas of Interest

- **Artificial Intelligence**: Machine learning, neural networks, and search algorithms
- **Computational Biology**: Genetic algorithms, cellular automata, and their real-world applications in biological systems
- **Theoretical Computer Science**: Algorithm design, automata theory, and emergent computational paradigms
- **Full-Stack Development**: Building scalable, interactive, and user-friendly web applications

---

# 📂 Featured Projects

## 📊 Data Science & Machine Learning

### [Search By Ingredients](https://github.com/v1t3ls0n/search_by_ingredients)

A multi-diet, portion-aware recipe search and transformation system. Evolved from Argmax's challenge into a full product with real-time analysis, scoring, and conversion for Keto, Vegan, or both, with dynamic substitutions and an interactive UI.

Version 3.0 is now in progress, adding a local-first RAG Chat interface with multi-turn memory, citations, and tool-use for searching, transforming, and exporting recipes through natural language.

**Highlights:**
- Portion-aware classification with practical compliance thresholds (e.g., `#keto:0.8`)
- Multi-diet logic, real-time scoring, and visual diet badges
- One-click recipe conversion via dynamic substitution engine
- Ingredient-level analysis UI and saved variations with unique ID management
- API and CLI for search, batch conversion, and export
- RAG Chat integration with local LLMs, structured tool-calls, and source-grounded answers

**Keywords:** Diet Classification, Recipe Transformation, Portion-Aware Analysis, Multi-Diet Logic, RAG Chat, LLM Tool Use, Data Science, Machine Learning, API, UI

---

### [Ariel Exoplanet Spectra Reconstruction Pipeline](https://colab.research.google.com/drive/1tGD3S9ZzeiyFMFoYYJJwRSQVB7U_Ag5G)

**Tools:** Python, NumPy, Pandas, Scikit-learn, Matplotlib

A full end-to-end scientific pipeline that reconstructs exoplanet transmission spectra from simulated Ariel telescope data.

**Highlights:**
- Designed a multi-stage modular ML pipeline: calibration, noise reduction, transit detection, feature engineering, wavelength-wise regression, OOF cross-validation, and uncertainty modeling
- Implemented per-λ ridge regression models with systematic error handling, bootstrap resampling, and a custom SigmaPredictor for variance estimation
- Built clear separation between components (calibration → detection → regression → uncertainty), similar to agent tool-chains with deterministic execution steps
- Produced high-quality analysis, figures, and scientific storytelling aligned with NeurIPS-level expectations

**Keywords:** Exoplanet ML, Time-series modeling, Uncertainty estimation, Scientific pipelines, Regression per wavelength

---

### [From-Scratch ML Framework for MNIST](https://colab.research.google.com/drive/1hvCjOK-nPyG3-FCZtCjs202q7QQFwAAL)

**Tools:** Python, NumPy, CuPy

Built an end-to-end neural framework from scratch, without deep learning libraries.

**Highlights:**
- Implemented perceptrons, softmax regression, loss functions, AdaGrad, LR schedules, early stopping, and checkpointing manually
- Added GPU acceleration via CuPy for matrix operations
- Built custom diagnostics: convergence curves, gradient inspections, and model comparison utilities
- Demonstrates deep understanding of the internals behind modern ML systems and numerical optimization

**Keywords:** Numerical ML, Optimization algorithms, GPU computing, Educational ML framework

---

### [Stroke Prediction Classifier Pipeline](https://colab.research.google.com/drive/1NhB2y5tSh5HZeB8cjnmFCAi1LNv-9YEr)

**Tools:** Python, Scikit-learn, Pandas

A complete supervised classification pipeline for medical risk prediction.

**Highlights:**
- Full preprocessing workflow: imputation, medical feature discretization, normalization, SMOTE for imbalance
- Compared multiple models (Random Forest, SVM, Logistic Regression, Naive Bayes, C4.5)
- Included ROC/PRC curves, confusion matrices, threshold tuning, and metric interpretation
- Emphasized reliable evaluation and model behavior analysis, relevant for constructing robust decision systems

**Keywords:** Classification, Healthcare analytics, Model evaluation, Imbalanced data

---

## 🔬 Biological Computation

### [Genetic Algorithm - Methuselah Patterns](https://github.com/v1t3ls0n/GeneticAlgorithm-MethuselahPatterns)

A genetic algorithm implementation designed to discover Methuselah patterns in Conway's Game of Life. Methuselah patterns are small initial configurations that evolve for many generations before stabilizing.

**Highlights:**
- Explored evolutionary approaches to optimize and analyze pattern behavior
- Integrated visualization tools to study dynamic evolution in real-time

**Keywords:** Genetic Algorithm, Conway's Game of Life, Methuselah Patterns, Computational Biology

---

### [3D Cellular Automaton (Climate System Simulation)](https://github.com/v1t3ls0n/3D-Cellular-Automaton-Climate-Simulation)

A simulation of cellular automata developed as part of the Biological Computation course. This project explores emergent behaviors in systems and their applications, such as modeling environmental and climate-based models.

**Highlights:**
- Designed custom automata rules for advanced simulations
- Utilized Python with Tkinter for visualization and statistical analysis of system dynamics
- Investigated environmental and climate-based models through computational experiments

**Keywords:** Cellular Automaton, Climate Simulation, Computational Biology

---

### [DNA-fountain](https://github.com/v1t3ls0n/DNA-fountain)

This project demonstrates a simplified DNA Fountain encoding and decoding system. It encodes binary data into "droplets" (small units) using an XOR-based combination of data chunks and maps the resulting binary data to a DNA sequence using the nucleotides A, C, G, T.

**Highlights:**
- Implemented DNA Fountain coding for data storage in DNA
- Demonstrated encoding and decoding processes

**Keywords:** DNA Fountain, Data Storage, Computational Biology

---

## 🖥️ Low-Level Programming

### [Assembler](https://github.com/v1t3ls0n/assembler)

A custom assembler written in C as part of the Systems Programming Lab course at the Open University of Israel. The assembler translates assembly language instructions into machine code for a specific architecture.

**Highlights:**
- Implemented instruction parsing and error handling for assembly programs
- Designed a robust system for macro expansion and machine code generation
- Demonstrated low-level programming expertise and a deep understanding of systems programming

**Keywords:** Assembler, C Programming, Systems Programming, Low-Level Programming

---

## 🌐 Full-Stack Development

### [Tempe Weather SPA](https://github.com/v1t3ls0n/tempe-weather-spa)

A single-page weather forecast application designed with modern web technologies. The app integrates React.js for the frontend, Node.js for the backend, and MongoDB for data storage, leveraging a REST API for weather data retrieval.

**Highlights:**
- Developed a responsive UI with React and REST API integration
- Full-stack implementation showcasing robust backend and frontend interaction

**Keywords:** SPA, Node.js, React.js, MongoDB, Weather Forecast API

---

### [OpenU Grades Avg Calc Chrome Extension](https://github.com/v1t3ls0n/Openu_Grades_Avg_Calc_Chrome_Browser_Extension)

A Chrome extension created for Open University students to calculate their GPA and plan future grades using various methods.

**Highlights:**
- Provided a user-friendly interface for practical academic assistance
- Designed to streamline student grade calculations and progress tracking

**Keywords:** Chrome Extension, Academic Tools, GPA Calculator

---

### [MayPortfolio](https://github.com/v1t3ls0n/mayportfolio)

A responsive portfolio website built for May Vitelson, showcasing her UX/UI design with elegant and functional frontend implementation.

**Highlights:**
- Collaboration-focused project with UX/UI and development integration
- Frontend development optimized for user experience and responsiveness

**Keywords:** Portfolio Website, Frontend Development, Collaboration

---

# 📚 About Me

- 🌱 Currently exploring the intersection of **theoretical computer science** and **AI-driven solutions**
- 💻 Passionate about **bridging theory and practical application** through innovative projects
- 🎯 Open to collaborations, research, and professional opportunities

---

# 📫 How to Reach Me

- [LinkedIn](https://www.linkedin.com/in/guyvitelson/)
- [GitHub](https://github.com/v1t3ls0n)

Thank you for visiting my profile! I'm eager to connect, learn, and contribute to impactful projects in computer science and beyond. 🚀
