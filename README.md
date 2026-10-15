<div align="center">

# Hi, I'm Mohamed Boukaf 👋

<a href="https://github.com/mboukaf">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=2F81F7&center=true&vCenter=true&width=640&lines=Scientific+machine+learning;Physics-informed+%C2%B7+uncertainty-aware+%C2%B7+certified;Teaching+neural+networks+some+physics;Learning+dynamics%2C+observers+%26+controllers" alt="Scientific machine learning · Physics-informed, uncertainty-aware, certified" />
</a>

![PhD](https://img.shields.io/badge/PhD_candidate-Inria_%C2%B7_Paris--Saclay-E63312?style=flat-square)
![Location](https://img.shields.io/badge/Based_in-Paris_area-555?style=flat-square)
<!-- Add your links here, e.g.:
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=flat-square&logo=googlescholar&logoColor=white)](YOUR_SCHOLAR_URL)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](YOUR_LINKEDIN_URL)
-->

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/observer-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/observer-light.svg">
  <img alt="Animation: a learned observer starts from a wrong initial guess and locks onto the true state of a Van der Pol oscillator while the estimation error drops by more than two orders of magnitude" src="assets/observer-light.svg" width="100%">
</picture>

<sub>A neural-network observer I trained, rebuilding the full state of a Van der Pol oscillator from a single noisy, delayed measurement.</sub>

</div>

---

### 🧭 About me

I work on **scientific machine learning**: the place where neural networks meet differential equations, physical structure and real measurements.

I trained as a control engineer and then as a data scientist, and I'm now a PhD candidate at Inria / Université Paris-Saclay. I like models that learn from data but still respect the physics, say how uncertain they are, and come with a proof when it matters. My thesis is on learning-based state estimation, but that is one corner of a much wider interest.

### 🔬 What I'm curious about

<table>
<tr>
<td width="50%" valign="top">
<b>🧪 Physics-informed learning</b><br/>
PINNs, hard physical constraints, neural operators (FNO, DeepONet, PINO)
</td>
<td width="50%" valign="top">
<b>🌊 Learning dynamical systems</b><br/>
Neural ODEs, system identification, Koopman and reduced-order models
</td>
</tr>
<tr>
<td valign="top">
<b>🔁 Sequence models for dynamics</b><br/>
Transformers that learn filters in context, state-space models like Mamba
</td>
<td valign="top">
<b>🎲 Uncertainty quantification</b><br/>
Conformal prediction, Gaussian processes, Bayesian PINNs
</td>
</tr>
<tr>
<td valign="top">
<b>🛡️ Certified &amp; safe learning</b><br/>
Lyapunov, barrier and contraction certificates; Lipschitz-bounded and stable-by-design networks
</td>
<td valign="top">
<b>🌀 Generative &amp; representation learning for science</b><br/>
Diffusion over function spaces, self-supervised encoders, JEPA-style world models
</td>
</tr>
</table>

**Where I like to apply it:** 🫀 cardiovascular modeling · 🦿 neuromuscular control · 🚁 aerial robotics · 🧠 neural and chaotic oscillators

### 🗺️ How I think about SciML

```mermaid
flowchart LR
    D["📊 Data<br/>noisy, partial, scarce"] --> L
    P["⚛️ Physics<br/>ODEs, PDEs, structure"] --> L
    L["🧠 Learn<br/>PINNs · neural ODEs<br/>operators · transformers"] --> T["🛡️ Trust<br/>uncertainty · certificates"]
    T --> U["🚀 Use<br/>estimation · control · prediction"]
```

### 📐 SciML in one line

```math
\min_{\theta}\;
\underbrace{\frac{1}{N}\sum_{i=1}^{N}\big\|u_\theta(x_i)-u_i\big\|^2}_{\text{fit the data}}
\;+\;\lambda\,
\underbrace{\frac{1}{M}\sum_{j=1}^{M}\big\|\mathcal{N}[u_\theta](x_j)\big\|^2}_{\text{respect the physics}}
```

The question I care about most comes after training: **how far can we trust $u_\theta$ where it never saw any data?**

### 🧰 My stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Julia](https://img.shields.io/badge/Julia-9558B2?style=for-the-badge&logo=julia&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB_%2F_Simulink-0076A8?style=for-the-badge)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)

| Area | Tools |
|---|---|
| **Deep learning** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![torch.func](https://img.shields.io/badge/torch.func-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![JAX](https://img.shields.io/badge/JAX_%28exploring%29-5E97F6?style=flat-square) |
| **Scientific computing** | ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square) ![seaborn](https://img.shields.io/badge/seaborn-4C72B0?style=flat-square) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) |
| **Optimization & control** | ![CVXPY](https://img.shields.io/badge/CVXPY-2D6DB5?style=flat-square) ![JuMP + Ipopt](https://img.shields.io/badge/JuMP_%2B_Ipopt-4063D8?style=flat-square&logo=julia&logoColor=white) ![ForwardDiff.jl](https://img.shields.io/badge/ForwardDiff.jl-9558B2?style=flat-square&logo=julia&logoColor=white) ![Optuna](https://img.shields.io/badge/Optuna-2C5BB4?style=flat-square&logo=optuna&logoColor=white) |
| **LLMs & data** | ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square) ![sentence-transformers](https://img.shields.io/badge/sentence--transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![RAGAS](https://img.shields.io/badge/RAGAS-6B46C1?style=flat-square) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white) |
| **Infra & workflow** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![SLURM](https://img.shields.io/badge/SLURM_%2F_HPC-0F6E8C?style=flat-square) ![AWS](https://img.shields.io/badge/AWS_%28S3%2C_RDS%29-FF9900?style=flat-square) ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) |
| **Research & writing** | ![LaTeX / Beamer](https://img.shields.io/badge/LaTeX_%2F_Beamer-008080?style=flat-square&logo=latex&logoColor=white) ![Zotero](https://img.shields.io/badge/Zotero-CC2936?style=flat-square&logo=zotero&logoColor=white) ![Obsidian](https://img.shields.io/badge/Obsidian-7C3AED?style=flat-square&logo=obsidian&logoColor=white) |

**How I actually use them**
- **PyTorch + `torch.func`** (`vmap`, `jacrev`) to compute batched Jacobians, so I can train networks against conditions that hold *everywhere* in the state space, not only on average
- **CVXPY** for LMI/SDP baselines, and **Julia (JuMP + Ipopt)** for nonlinear model predictive control
- **Optuna** sweeps launched as **SLURM** jobs on HPC clusters; experiments driven by YAML configs and tested with **pytest**
- A full **RAG pipeline**: open-archive API → PostgreSQL → embeddings in ChromaDB → LangChain, evaluated with RAGAS, served with Streamlit, with the AWS infrastructure written in Terraform

### 🛠️ Things I've built

- **[PIBE](https://github.com/mboukaf/-E-PIBE)**: a physics-informed bank of estimators that recovers states, parameters and disturbances from a single noisy output *(framework presented at ECC 2026)*
- **[PigsPretraining](https://github.com/mboukaf/PigsPretraining)**: self-supervised representation learning on multichannel cardiovascular signals
- **Certified learned observers & controllers**: neural contraction metrics for estimation and trajectory tracking *(CDC 2026)*, and observers that cope with delayed measurements
- **Physics-informed cardiovascular models**: PINNs for Windkessel models of arterial blood pressure
- **KKL observers + stochastic NMPC** for neuromuscular co-contraction, in Julia
- **A research assistant for my team**: retrieval-augmented generation over our publications

### 📚 Books on my desk

- *Data-Driven Science and Engineering: Machine Learning, Dynamical Systems, and Control*, Steven L. Brunton & J. Nathan Kutz
- *Observer Design for Nonlinear Systems*, Pauline Bernard
- *Mathematical Foundations of Deep Learning: Theory and Algorithms*, Xiaojing Ye
- *The Elements of Statistical Learning*, Trevor Hastie, Robert Tibshirani & Jerome Friedman
- *Time Series with PyTorch*, Graeme Davidson & Lei Ma
- *50 ML Projects to Understand LLMs*, Mike X Cohen

### 🎓 Background

- **PhD**, Université Paris-Saclay / Inria, on learning-based observers with formal guarantees
- **MSc Data Science**, Télécom SudParis
- **Control engineering degree**, École Nationale Polytechnique (Algiers)

### 🌄 Beyond the code

- 🏃 Trail running
- 👨‍🏫 Teaching feedback control at IUT de Cachan
- 🗣️ French · English
- 💬 Always up for a chat about SciML, uncertainty and learning for control

<div align="center">
<sub>Fit the data. Respect the physics. Quantify the doubt.</sub>
</div>
