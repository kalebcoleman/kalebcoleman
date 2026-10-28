<div align="center">

# Hey, I'm Kaleb Coleman 👋

### Data Science Student | AI + Robotics | Simulation, Controls, and Machine Learning

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Kaleb%20Coleman-blue?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kaleb-coleman-a1807a284)
[![GitHub](https://img.shields.io/badge/GitHub-kalebcoleman-black?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kalebcoleman)

<img src="https://komarev.com/ghpvc/?username=kalebcoleman&style=flat-square&color=blue" alt="Profile views"/>

</div>

---

## About Me

I am a Data Science undergraduate student at Northern Arizona University with a minor in Cybersecurity. After graduation, I plan to continue into graduate school at Arizona State University for Artificial Intelligence Engineering with a focus on robotics.

My work sits where data science meets robotics: machine learning and data pipelines on one side, simulation, control, and autonomous systems on the other. This past year I moved from analytics and deep learning projects into hands-on robotics research in simulation, covering bimanual manipulation in NVIDIA Isaac Sim and prescribed-time control for quadrotors.

I care about reproducible, honestly reported results: every claim should trace to a run, a log, or a saved artifact, and limitations get written down next to the numbers.

---

## Technical Skills

| Programming Languages | Tools and Libraries | Areas of Interest |
| --- | --- | --- |
| Python<br>R<br>C<br>SQL<br>JavaScript<br>TypeScript | PyTorch<br>scikit-learn<br>XGBoost<br>pandas and NumPy<br>NVIDIA Isaac Sim / Isaac Lab<br>MuJoCo<br>Streamlit<br>PostgreSQL and SQLite<br>Linux, Git and GitHub | Robotics and Manipulation<br>Control and Optimization<br>Digital Twins and Sim-to-Real<br>Deep Learning<br>Computer Vision<br>Data Engineering<br>Cybersecurity |

---

## Robotics and Autonomy Research

| Project | What I'm doing |
| --- | --- |
| **[Two-arm manipulation in Isaac Sim](https://github.com/kalebcoleman/rise-two-arm-research)** *(RISE lab)* | Two opposing UR5e arms with RG2 grippers holding a shared bar in Isaac Sim 5.1. I added collision setup and validation, corrected joint frames, object-space goals with per-arm IK, and grasp, lift, and coordinated-motion experiments. The accepted run held four-finger contact for 100% of samples with 0 unexpected collisions, max slip 0.135 mm, and max tracking error 2.02 mm. I also mapped the load and speed limits of the setup (1.25 kg passed at baseline speed, 1.5 kg exceeded the drift bound). |
| **Digital twin and sim-to-real** *(in progress)* | The current model is a simulation, not yet a calibrated twin. Next: measure the real workstation (base, tool, and camera transforms, joint offsets, mass and inertia, gripper and actuator behavior, latency), then calibrate on one dataset and evaluate on held-out conditions. |
| **Energy-Aware Prescribed-Time Quadrotor Control** *(with John Lok)* | Extending the IM-NMPO framework with user-selected tracking deadlines, motor-lag and drag modeling, wind estimation, and energy-aware planning on an S500-based MuJoCo test bench. Simulation comparisons, a held-out system-identification study, a paper draft, and a plan for hardware flight tests starting in November 2026. Reported results are simulation only and I label which ones are independently reproduced. |

**Tools and skills:** NVIDIA Isaac Sim and Isaac Lab, USD scene authoring, MuJoCo, UR5e/RG2 manipulation, inverse kinematics, model predictive control, system identification, MCP-based simulator tooling, Linux/GPU workstation setup.

---

## Featured Work

- Won **Best Visualization** at ASA DataFest; the 2026 project modeled early signals of high healthcare utilization.
- Built a leakage-aware NBA modeling pipeline with time-safe validation, plus an end-to-end ESPN data engineering pipeline in R.
- Compared autoencoders, PCA, denoising autoencoders, VAEs, and diffusion models for image reconstruction.
- Developed NBA/NHL expected-points analysis for my NAU capstone and Streamlit dashboards to communicate results.
- Trained models on GPU and HPC resources.

---

## Featured Public Repositories

| Repository | Focus |
| --- | --- |
| [rise-two-arm-research](https://github.com/kalebcoleman/rise-two-arm-research) | Two UR5e arms with RG2 grippers manipulating a shared bar in Isaac Sim 5.1, with validated motion, evidence, and reproducible setup. |
| [ImageReconstruction](https://github.com/kalebcoleman/ImageReconstruction) | Image reconstruction using autoencoders, PCA, denoising autoencoders, VAEs, and diffusion-style approaches. |
| [deep-learning-projects](https://github.com/kalebcoleman/deep-learning-projects) | Deep learning experiments and coursework projects exploring neural networks, model training, and applied AI concepts. |
| [nba-modeling](https://github.com/kalebcoleman/nba-modeling) | Leakage-aware NBA win modeling with rolling metrics, time-safe validation, and a reproducible pipeline, with a research paper. |
| [nba-data](https://github.com/kalebcoleman/nba-data) | End-to-end ESPN NBA data engineering pipeline in R: raw JSON to validated tables, RDS/CSV/SQLite with versioned migrations. |
| [halma-ai](https://github.com/kalebcoleman/halma-ai) | Halma game AI using iterative-deepening minimax with alpha-beta pruning, a Tkinter GUI, and a benchmarking arena. |
| [ai-multitool-assistant](https://github.com/kalebcoleman/ai-multitool-assistant) | Full-stack ReAct agent app: Django REST backend, React (Vite) frontend, OpenAI and LlamaIndex. |
| [nau-capstone](https://github.com/kalebcoleman/nau-capstone) | NAU capstone: NBA/NHL expected-points analysis. |
| [malware-analysis](https://github.com/kalebcoleman/malware-analysis) | Cybersecurity coursework on malware analysis concepts and reverse engineering. |

My two-arm Isaac Sim research is public in [rise-two-arm-research](https://github.com/kalebcoleman/rise-two-arm-research). The quadrotor control work with John Lok is in a private collaborative repository; happy to walk through it on request.

---

## What I'm Working Toward

**Now:** calibrating the Isaac Sim two-arm setup toward a real digital twin, reproducing and improving the prescribed-time quadrotor controller, and preparing for hardware flight tests.

**Next:** graduate study in AI Engineering with a robotics focus at Arizona State University, aimed at sim-to-real transfer, learning-based and optimal control, drones, and space systems.

---

## Hobbies

Outside of school and coding, I enjoy sports, gaming, technology, learning about AI, and working on projects that help me grow as a developer and researcher.

---

## Languages and Tools

<div align="center">

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="45" height="45" alt="Python"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/r/r-original.svg" width="45" height="45" alt="R"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" width="45" height="45" alt="C"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="45" height="45" alt="JavaScript"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" width="45" height="45" alt="PyTorch"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="45" height="45" alt="Linux"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="45" height="45" alt="PostgreSQL"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlite/sqlite-original.svg" width="45" height="45" alt="SQLite"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="45" height="45" alt="Git"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="45" height="45" alt="GitHub"/>

</div>

---

## GitHub Stats

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=kalebcoleman&theme=dracula" alt="Kaleb's GitHub profile summary"/>

<img src="https://streak-stats.demolab.com?user=kalebcoleman&theme=dracula&date_format=M%20j%5B%2C%20Y%5D" alt="Kaleb's GitHub streak"/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=kalebcoleman&theme=dracula" alt="Kaleb's top languages"/>

</div>

---

## Connect With Me

- LinkedIn: [Kaleb Coleman](https://www.linkedin.com/in/kaleb-coleman-a1807a284)
- GitHub: [kalebcoleman](https://github.com/kalebcoleman)
