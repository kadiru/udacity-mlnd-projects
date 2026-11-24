# Machine learning, one question at a time.

An archive of **Kadir Uyanik's Udacity Machine Learning Nanodegree coursework**, including a capstone on recognizing human activity from smartphone sensor data. The notebooks show problem framing, data exploration, model comparisons and written evaluation.

This is educational work built on course-provided scaffolding and public datasets. It is separate from the robotics research and product projects on my profile.

## Explore the projects

| Question | Notebook | Focus |
| --- | --- | --- |
| What activity is a person performing? | [Capstone](capstone/capstone.ipynb) | Smartphone sensor-based activity recognition |
| How can a model estimate a house price? | [Boston housing](boston_housing/boston_housing.ipynb) | Regression, model selection and evaluation |
| Which students may need support? | [Student intervention](student_intervention/student_intervention.ipynb) | Supervised classification and tradeoffs |
| What structure appears in customer data? | [Customer segments](customer_segments/customer_segments.ipynb) | Unsupervised exploration and clustering |
| How can an agent learn driving decisions? | [Smartcab](smartcab/smartcab.ipynb) | Reinforcement learning in a course simulator |

## Start with the capstone

Read the [notebook](capstone/capstone.ipynb) or download its [rendered HTML](capstone/capstone.html). The [dataset note](capstone/README.txt) credits Anguita et al.'s *A Public Domain Dataset for Human Activity Recognition Using Smartphones* (ESANN 2013). Results belong to the notebook's historical protocol; this overview does not present them as a current benchmark.

For implementation, the [Smartcab agent](smartcab/smartcab/agent.py) provides a compact route into a learning loop; its environment and simulator are course infrastructure.

## Reproduction status

These notebooks retain their original dependencies and assumptions. Start with each project's README and recorded imports; a clean environment has not been restored for this documentation pass. There is no claimed current one-command build.

This is a completed learning archive. A future refresh would pin an environment, rerun one notebook from a clean kernel and compare the new output with the saved report before changing the others. Course and dataset attribution remains in the individual projects.
