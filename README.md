# EMT_Alon_Model

A Python-based agent-based model that simulates wound healing dynamics in mouse alveolar epithelial tissue, incorporating age-dependent senescent cell behavior using principles from Alon’s aging model. This project integrates biological rules of epithelial-mesenchymal transition (EMT), cell migration, proliferation, and senescence to investigate how aging impairs tissue repair.

## 📖 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Description](#model-description)
- [Directory Structure](#directory-structure)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## 🧬 Overview

Chronic damage and aging in lung tissue impair epithelial wound healing, contributing to diseases such as pulmonary fibrosis. This project implements a biologically informed simulation to study how age-driven senescence affects the alveolar epithelial tissue during wound repair. By modeling the progression of senescence and reduced clearance capacity with age, we aim to predict wound closure outcomes and tissue permeability in aging tissue.

## 🚀 Features

- 🧠 **Senescence Modeling**: Implements Alon’s age-dependent senescent cell dynamics.
- 🔁 **Cell State Transitions**: Alive, dividing, migrating, senescent, and dead states with probabilistic transitions.
- 🏃 **Density-Directed Migration**: Simulates collective cell migration based on local density gradients.
- ⏳ **Age-Dependent Behaviors**: Senescence probability and removal rate scale with tissue age.
- 📊 **Data Export**: Outputs simulation metrics and plots such as wound closure time, permeability, dividng and migrating cell counts in time (hour).
- 📉 **Visualization**: Includes tools for 2D grid visualization and parameter sweep analysis.

## 🛠 Installation

```bash
git clone https://github.com/jiho1999/EMT_Alon_Model.git
cd EMT_Alon_Model
pip install -r requirements.txt
