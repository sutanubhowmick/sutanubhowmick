## Sutanu Bhowmick

**Agentic AI Architect** · The Home Depot · PhD, Rice University · Washington, DC

I build AI systems at enterprise scale and own them end to end: architecture,
deployment, and the monitoring that keeps them running afterwards. What I am
measured on is the business result, not the model.

At The Home Depot I lead agentic AI initiatives, building multi-agent pipelines on
frontier models that handle multi-step workflows with little human intervention.
My work also covers multimodal AI, computer vision, and MLOps.

Nine years in, the pattern I keep seeing is that the model is rarely what decides a
project. Evaluation, cost, latency, and failure handling decide it. That is where
the results come from too: cost reduced by automating manual work, multimodal
systems that beat the baselines they were measured against, and pipelines that stay
up under real load.

### SNAPE

SNAPE is a method I developed during my PhD for a problem that shows up everywhere
in engineering and science. You have a physical model, you have noisy measurements,
and you need the model's parameters.

The standard approach differentiates the measurements numerically. Noise makes that
unreliable, and the higher the derivative the worse it gets, so published methods
start failing at a few percent of noise. SNAPE never differentiates the data. It
fits smooth basis functions to the measurements and solves for the physical
parameters at the same time, so every derivative comes from the fitted function
instead of the raw signal. It does not need the initial or boundary conditions, and
it reports uncertainty bounds alongside the parameters.

It recovers the parameters of Burgers' equation from data carrying 100% Gaussian
noise, and identifies a fifth-order Euler–Bernoulli beam model from ordinary video
of a vibrating beam. It applies anywhere a known physical model has to be calibrated
from noisy sensor data: structural and machine digital twins, medical imaging, power
grid dynamics, thermal testing.

SNAPE exists because deep learning was not repeatable enough for this problem.
Knowing when a model is wrong, and how much to trust it when it is right, is the
same discipline that decides whether an AI system is safe to run at scale.

**An open-source implementation and interactive demonstrations are in preparation.**

### Selected publications

Over 1,500 citations, mostly in structural health monitoring, computer vision for
civil infrastructure, and parameter estimation.

- *Data- and theory-guided learning of partial differential equations using SimultaNeous
  basis function Approximation and Parameter Estimation (SNAPE)*, Mechanical Systems
  and Signal Processing 189 (2023) 110059.
  [10.1016/j.ymssp.2022.110059](https://doi.org/10.1016/j.ymssp.2022.110059)
- *Physics-guided identification of Euler–Bernoulli beam PDE model from full-field
  displacement response with SNAPE*, Engineering Structures 289 (2023) 116231.
  [10.1016/j.engstruct.2023.116231](https://doi.org/10.1016/j.engstruct.2023.116231)
- *Review of bridge structural health monitoring aided by big data and artificial
  intelligence: from condition assessment to damage detection*, Journal of Structural
  Engineering 146 (2020).
  [10.1061/(ASCE)ST.1943-541X.0002535](https://doi.org/10.1061/(ASCE)ST.1943-541X.0002535)
- *Measurement of full-field displacement time history of a vibrating continuous edge
  from video*, Mechanical Systems and Signal Processing 144 (2020) 106847.
  [10.1016/j.ymssp.2020.106847](https://doi.org/10.1016/j.ymssp.2020.106847)

### Links

[sutanubhowmick.com](https://sutanubhowmick.com) ·
[LinkedIn](https://www.linkedin.com/in/sutanubhowmick/) ·
[Google Scholar](https://scholar.google.com/citations?user=-pgkA6MAAAAJ) ·
[ORCID 0000-0001-9350-4803](https://orcid.org/0000-0001-9350-4803)
