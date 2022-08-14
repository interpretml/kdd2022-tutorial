# [KDD 2022 Tutorial] Why Data Scientists Prefer Glassbox Machine Learning: Algorithms, Differential Privacy, Editing and Bias Mitigation 

![](https://github.com/interpretml/interpretml.github.io/blob/master/interpret-highlight.gif)

## Tutorial Abstract

Recent research has shown that interpretable machine learning models can be just as accurate as blackbox learning methods on tabular datasets. In this tutorial we will walk you through leading open source tools for glassbox learning, and show how intelligible machine learning helps practitioners uncover flaws in their datasets, discover new science, and build models that are more fair and robust. We’ll begin with an introduction to the science behind glassbox modeling, and walk through a series of case-studies that highlight the added value of interpretable methods in a variety of domains such as finance and healthcare without compromising accuracy. We’ll also show how glassbox models can be used for state of the art differentially private learning, bias detection/mitigation, and how these models can be edited to remove undesirable effects with GAMChanger. We’ll also discuss how to train interpretable models with deep neural nets.

## Outline

- Introduction to Glassbox Models (30 min)
    - Explainable Boosting Machines (EBMs)
    - Glassbox vs. Blackbox Explanations
- Case Studies (60 min)
    - Healthcare
    - Industry
    - Finance
    - Missing Values Meets Glassbox Learning
    - Bias and Fairness

- InterpretML Software: Intro and Installation (15 min,  hands-on)
- Differential Privacy (45 min, hands-on)
    - Introduction to Differential Privacy
    - DP Explainable Boosting Machines
    - Mitigating impacts of DP noise with interpretable, editable models

- Model Editing (15 min, hands-on)


## Tutors and Bios

<!-- ![Rich Caruana](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/07/avatar_user_33365_1499288470-360x360.jpg) -->
<img src="https://www.microsoft.com/en-us/research/wp-content/uploads/2017/07/avatar_user_33365_1499288470-360x360.jpg" width="360" />


[Rich Caruana @ Microsoft Research](https://www.microsoft.com/en-us/research/people/rcaruana/)

- Rich Caruana is a senior principal researcher at Microsoft Research. Before joining Microsoft, Rich was on the faculty in the Computer Science Department at Cornell University, at UCLA’s Medical School, and at CMU’s Center for Learning and Discovery.  Rich’s Ph.D. is from Carnegie Mellon University, where he worked with Tom Mitchell and Herb Simon.  His thesis on Multi-Task Learning helped create interest in a new subfield of machine learning called Transfer Learning.  Rich received an NSF CAREER Award in 2004, best paper awards in 2005, 2007, 2014, and 2021 co-chaired KDD in 2007, and serves as area chair for NIPS, ICML, and KDD. His current research focus is on learning for medical decision making, transparent modeling, and deep learning.
    
<!-- ![Harsha Nori](https://www.microsoft.com/en-us/research/uploads/prod/2022/07/harsha_profile_pic.jpg) -->
<img src="https://www.microsoft.com/en-us/research/uploads/prod/2022/07/harsha_profile_pic.jpg" width="360" />

[Harsha Nori @ Microsoft Research](https://www.microsoft.com/en-us/research/people/hanori/)
- Harsha Nori is a senior research engineering manager at Microsoft Research, working on Responsible AI tools. He co-founded the popular InterpretML toolkit, and has contributed to a number of popular open source data science tools. His current research focus is on explainability, fairness, and differential privacy for machine learning, and has published on these topics at conferences including NeurIPS, ICML, AAAI, CHI, and CLeaR, with a best paper at the 2021 NeurIPS Research2Clinics workshop. 

<br>

## Environment Setup

Note that M1/M2 based Mac devices require a slightly modified setup process. Please scroll down for detailed instructions on these devices.

1) [*Optional*] For an isolated Python environment, setup the conda environment manager:

- Install Miniconda, choosing the correct 64-bit version at this URL for your computer architecture: https://docs.conda.io/en/latest/miniconda.html#latest-miniconda-installer-links

- Create a new conda environment: `conda create -n interpret python=3.8`

- Activate your newly created environment: `conda activate interpret`

2) Install required packages on the command line: `pip install interpret gamchanger jupyter`

3) Clone this repository: `git clone https://github.com/interpretml/kdd2022-tutorial.git`

4) Launch Jupyter: `cd kdd2022-tutorial && jupyter notebook`

### Setup Instructions for M1/M2 based Macs

1) Install Rosetta 2 and create a Rosetta-enabled terminal, following this guide: https://www.byran.tech/html/how-to-make-a-rosetta-2-emulated-x86-terminal-on-arm-apple-silicon-chips.html

2) Launch your new Rosetta-enabled Terminal

3) Install Miniconda: https://docs.conda.io/en/latest/miniconda.html#latest-miniconda-installer-links

4) Create and activate a new x86-enabled conda environment: 
```
CONDA_SUBDIR=osx-64 conda create -n interpret python=3.8
conda activate interpret
conda config --env --set subdir osx-64
```

5) Follow steps 2-4 above :)


<br/>
<br/>
<br/>
<br/>
<br/>

<br/>
<br/>
<br/>
<br/>
<br/>

<br/>
<br/>
<br/>
<br/>
<br/>

<br/>
<br/>
<br/>
<br/>
<br/>

<br/>
<br/>
<br/>
<br/>
<br/>

<br/>
<br/>
<br/>
<br/>
<br/>

<br/>
<br/>
<br/>
<br/>
<br/>

<br/>
<br/>
<br/>
<br/>
<br/>

> ### Why do you think they call them “hidden units”? Use glassbox machine learning.















