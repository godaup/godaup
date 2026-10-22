<h1 align="center">Hi, I'm Patrick 👋</h1>

<p align="center">
  <b>I build AI for safer surgery, and the tools to check that it actually works.</b><br>
  Postdoctoral researcher at the <a href="https://www.dkfz.de/en/imsy/">German Cancer Research Center (DKFZ)</a> in Heidelberg, Germany
</p>

<p align="center">
  <a href="https://godaup.github.io/"><img src="https://img.shields.io/badge/Homepage-godaup.github.io-0a66c2?style=flat-square&logo=githubpages&logoColor=white" alt="Homepage"></a>
  <a href="https://scholar.google.com/citations?user=VRcPeykAAAAJ"><img src="https://img.shields.io/badge/Google%20Scholar-Publications-4285F4?style=flat-square&logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
  <a href="https://orcid.org/0000-0002-0365-7265"><img src="https://img.shields.io/badge/ORCID-0000--0002--0365--7265-A6CE39?style=flat-square&logo=orcid&logoColor=white" alt="ORCID"></a>
  <a href="https://www.dkfz.de/en/employees/patrick-godau"><img src="https://img.shields.io/badge/DKFZ-Profile-00589C?style=flat-square" alt="DKFZ profile"></a>
  <img src="https://komarev.com/ghpvc/?username=godaup&color=blue&style=flat-square" alt="Visit counter">
</p>

---

### 🔭 What I'm working on

- 🩺 Leading the **Intelligent Systems in Surgery and Endoscopy (ISSE)** subgroup in [Lena Maier-Hein's](https://www.dkfz.de/en/imsy/our-team) Division of Intelligent Medical Systems
- 🧠 Training **surgical foundation models** on national HPC infrastructure, backed by a Gauss Centre for Supercomputing compute grant
- 🏁 Co-organizing the **[FOCUS Challenge](https://orena-focus-challenge.org/)** (Foreign Object Contextual Understanding for Safe Surgical AI) at MICCAI 2026
- 📏 Making AI validation rigorous: metrics, prevalence shifts, and rankings you can trust

**Research interests:** foundation models · surgical data science · transfer, meta- and lifelong learning · validation and benchmarking of medical AI

### 📰 Latest news

| | |
|---|---|
| 🏆 **2026** | [BVM Award](https://www.bvm-conf.org/de/bvm-award/) for the best thesis at the German Conference on Medical Image Computing |
| 🎓 **2026** | Taught *Biomedical Image Analysis Validation* at the [AMBIA summer school](https://ambia.fi.muni.cz/2026/) in Brno ([materials](https://github.com/godaup/ambia-2026-validation-practical)) |
| 🥇 **2025** | 1st place in the [RARE25 challenge](https://rare25.grand-challenge.org/) at MICCAI 2025 |
| 📄 **2025** | [Navigating prevalence shifts in image analysis algorithm deployment](https://doi.org/10.1016/j.media.2025.103504), published in *Medical Image Analysis* |
| 🎓 **2025** | PhD (*summa cum laude*) at Heidelberg University on [lifelong machine learning for biomedical image classification](https://archiv.ub.uni-heidelberg.de/volltextserver/37135/) |

### 🏆 Challenge track record

I like competing as much as I like organizing:

| Challenge | Result |
|---|---|
| [RARE25](https://rare25.grand-challenge.org/) · MICCAI 2025 | 🥇 1st place |
| [Critical View of Safety](https://www.cvschallenge.org/the-challenge) · MICCAI 2024 | 🥈 2nd overall, 🥇 1st in generalization |
| [PitVis](https://www.synapse.org/Synapse:syn51232283/wiki/621586) · MICCAI 2023 | 🥇 1st place, instrument recognition |
| [CholecTriplet2022](https://cholectriplet2022.grand-challenge.org/cholectriplet2022/) · MICCAI 2022 | 🥇 1st place, detection and classification |
| Endoscopy Computer Vision Challenge 2.0 · ISBI 2022 | 🥇 1st place, polyp detection |
| [GIANA](https://giana.grand-challenge.org/) · MICCAI 2021 | 🥇 1st place, polyp classification |

Plus a [MedIA Best Paper Award](https://miccai.org/index.php/about-miccai/awards/medical-image-analysis-best-paper-award/), two MICCAI Best Challenge Reviewer Awards (2020 🥇, 2023 🥈) and a [HIDA Datathon](https://www.helmholtz-hida.de/news/datathon-fuer-die-klimaforschung/) win.

### 📚 Selected publications

- **Navigating prevalence shifts in image analysis algorithm deployment.** *Medical Image Analysis*, 2025 · [paper](https://doi.org/10.1016/j.media.2025.103504) · [code](https://github.com/IMSY-DKFZ/prevalence-shifts)
- **Beyond Knowledge Silos: Task Fingerprinting for Democratization of Medical Imaging AI.** Preprint, 2024 · [arXiv](https://arxiv.org/pdf/2412.08763) · [code](https://github.com/IMSY-DKFZ/task-fingerprinting)
- **Deployment of image analysis algorithms under prevalence shifts.** MICCAI 2023, oral, shortlisted for Best Paper · [paper](https://doi.org/10.1007/978-3-031-43898-1_38)
- **Metrics Reloaded: recommendations for image analysis validation.** *Nature Methods* · [paper](https://www.nature.com/articles/s41592-023-02151-z) · [online tool](https://metrics-reloaded.dkfz.de/) · [code](https://github.com/Project-MONAI/MetricsReloaded)
- **Task Fingerprinting for Meta Learning in Biomedical Image Analysis.** MICCAI 2021, oral · [arXiv](https://arxiv.org/pdf/2107.03949)

Full list on [Google Scholar](https://scholar.google.com/citations?user=VRcPeykAAAAJ).

### 🛠️ Open source

**[`mml`](https://github.com/IMSY-DKFZ/mml): Medical Meta Learner.** I'm the main developer of this library for scalable deep learning across many image tasks. It handles dataset management, a configurable CLI for the full pipeline, resumable and parallel experiments, and plugins. It's built on

![PyTorch](https://img.shields.io/badge/PyTorch-ee4c2c?style=flat-square&logo=pytorch&logoColor=white)
![Lightning](https://img.shields.io/badge/Lightning-792ee5?style=flat-square&logo=lightning&logoColor=white)
![Hydra](https://img.shields.io/badge/Hydra-89b8cd?style=flat-square)
![Optuna](https://img.shields.io/badge/Optuna-2c5bb4?style=flat-square)
![timm](https://img.shields.io/badge/timm-ffd21e?style=flat-square&logo=huggingface&logoColor=black)
![albumentations](https://img.shields.io/badge/albumentations-cc0000?style=flat-square)
![kornia](https://img.shields.io/badge/kornia-5a2d82?style=flat-square)

[Docs](https://mml.readthedocs.io/en/latest/index.html) · `pip install mml-core`

### 🎲 Just for fun

| Project | What it is |
|---|---|
| 🐍 [**Snake Quest**](https://github.com/godaup/snake) | Snake, but every level adds a twist: a retro campaign of 40 levels and 8 bosses built with Pyxel |
| 🏛️ [**wonders**](https://github.com/godaup/wonders) | *Can you beat the machine?* A rules-checked engine for a 7 Wonders-style drafting game, with a trained network to play against in your browser |

---

<p align="center">
  📫 Reach me at <code>patrick.godau (at) dkfz-heidelberg.de</code>, or come say hi at MICCAI!
</p>
