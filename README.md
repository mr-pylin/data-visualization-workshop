# 📊 Data Visualization Workshop

[![License](https://img.shields.io/github/license/mr-pylin/data-visualization-workshop?color=blue)](https://github.com/mr-pylin/data-visualization-workshop/blob/main/LICENSE)
[![Python Version](https://img.shields.io/badge/Python-3.15.1-yellow?logo=python&logoColor=white)](https://www.python.org/downloads/release/python-3151/)
[![Code Style](https://img.shields.io/badge/code%20style-black-black.svg)](https://github.com/psf/black)
![Repo Size](https://img.shields.io/github/repo-size/mr-pylin/data-visualization-workshop?color=lightblue)
![Last Updated](https://img.shields.io/github/last-commit/mr-pylin/data-visualization-workshop?color=orange)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?color=brightgreen)](https://github.com/mr-pylin/data-visualization-workshop/pulls)
<!-- [![Codacy Badge](https://app.codacy.com/project/badge/Grade/9eb774b7945449cdb86029e9093b3c73)](https://app.codacy.com/gh/mr-pylin/data-visualization-workshop/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade) -->

A comprehensive guide to data visualization, covering **Matplotlib**, **Seaborn**, and **Plotly**. From basic plotting techniques to advanced customization, this workshop helps you tell effective data stories in data science and analysis.

## 📖 Table of Contents

### 📖 Matplotlib

1. [**Introduction**](./code/matplotlib/01-introduction.ipynb)
1. [**Core Plots**](./code/matplotlib/02-core-plots.ipynb)
1. [**Customization**](./code/matplotlib/03-customization.ipynb)
1. [**Advanced Layouts**](./code/matplotlib/04-advanced-layouts.ipynb)
1. [**Specialized Plots**](./code/matplotlib/05-specialized-plots.ipynb)

### 📖 Seaborn

### 📖 Plotly

## 📋 Prerequisites

- 👨‍💻 **Programming Fundamentals**
  - 🐍 Proficiency in **Python** (data types, control structures, functions, classes, etc.).
    - My Python Workshop: [**github.com/mr-pylin/python-workshop**](https://github.com/mr-pylin/python-workshop)
- 🔢 **Basic Knowledge of NumPy**
  - Understanding of NumPy arrays and basic operations.
    - My NumPy Workshop: [**github.com/mr-pylin/numpy-workshop**](https://github.com/mr-pylin/numpy-workshop)

## ⚙️ Setup

> [!IMPORTANT]
> This project requires Python **v3.10** or higher. For **optimal compatibility** and to **avoid potential issues** with dependencies, it is **strongly advised** that you use the Python version specified in the [**.python-version**](.python-version) file.

### 📝 List of Dependencies

[![ipykernel](https://img.shields.io/badge/ipykernel-7.4.0-ff69b4)](https://pypi.org/project/ipykernel/7.4.0/)
[![ipympl](https://img.shields.io/badge/ipympl-0.10.0-orange)](https://pypi.org/project/ipympl/0.10.0/)
[![ipywidgets](https://img.shields.io/badge/ipywidgets-8.1.9-red)](https://pypi.org/project/ipywidgets/8.1.9/)
[![matplotlib](https://img.shields.io/badge/matplotlib-3.11.2-green)](https://pypi.org/project/matplotlib/3.11.2/)
[![numpy](https://img.shields.io/badge/numpy-2.5.4-orange)](https://pypi.org/project/numpy/2.5.4/)
[![pandas](https://img.shields.io/badge/pandas-3.1.0-yellow)](https://pypi.org/project/pandas/3.1.0/)
[![plotly](https://img.shields.io/badge/plotly-7.1.0-cyan)](https://pypi.org/project/plotly/7.1.0/)
[![seaborn](https://img.shields.io/badge/seaborn-0.13.2-lightblue)](https://pypi.org/project/seaborn/0.13.2/)

### 📦 Installing Dependencies

#### 1️⃣ Method 1: uv (**Recommended** ✅)

- Use [**uv**](https://docs.astral.sh/uv/) for dependency management. It handles dependencies, virtual environments, and locking versions more efficiently than pip.  
- To install exact dependency versions specified in [**uv.lock**](./uv.lock) for consistent environments **without** installing the current project as a package:

  ```bash
  uv sync --no-install-project
  ```

#### 2️⃣ Method 2: pip

- Install all dependencies listed in [**requirements.txt**](./requirements.txt) using [**pip**](https://pip.pypa.io/en/stable/installation/):

  ```bash
  pip install -r requirements.txt
  ```

> [!CAUTION]
> Pip does not lock dependency versions as strictly as `uv`. You may encounter version conflicts or reproducibility issues. Only use this method if you know what you are doing.

### 🛠️ Usage Instructions

1. Open the root folder with [**VS Code**](https://code.visualstudio.com/) (`Ctrl/Cmd + K` followed by `Ctrl/Cmd + O`).
1. Open `.ipynb` files using the [**Jupyter extension**](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) integrated with **VS Code**.
1. Select the correct Python kernel and virtual environment where the dependencies were installed.
1. Allow **VS Code** to install any recommended dependencies for working with Jupyter Notebooks.

> [!NOTE]
>
> - Stick with the **exact dependency versions** specified in [**uv.lock**](./uv.lock) or [**requirements.txt**](./requirements.txt). The repository has been **tested** with these versions to ensure **compatibility** and **stability**.
> - This repository is **actively maintained**, and dependencies are **updated regularly** to the latest **stable** versions.
> - The **table of contents** embedded within **notebooks (`.ipynb` files)** may not function correctly on **GitHub**.
> - For an improved experience, open the notebooks **locally** or view them via [**nbviewer**](https://nbviewer.org/github/mr-pylin/data-visualization-workshop), rather than directly on **GitHub**.

## 🔗 Useful Links

### Matplotlib

- **Website**
  - The official website for Matplotlib, providing information, tutorials, and resources for the Matplotlib library
  - Official site: [matplotlib.org](https://matplotlib.org)
- **Documentation**
  - Comprehensive guide and reference for all functionalities and features of the Matplotlib library
  - Doc: [matplotlib.org/stable/index.html](https://matplotlib.org/stable/index.html)
- **Source Code**
  - Over 1000 contributors are currently working on Matplotlib!
  - Link: [github.com/matplotlib/matplotlib](https://github.com/matplotlib/matplotlib)
- **Cheatsheets & Handouts**
  - Cheatsheets [pdf]:
    - [matplotlib.org/cheatsheets/cheatsheets.pdf](https://matplotlib.org/cheatsheets/cheatsheets.pdf)
  - Handouts [pdf]:
    - beginner: [matplotlib.org/cheatsheets/handout-beginner.pdf](https://matplotlib.org/cheatsheets/handout-beginner.pdf)
    - intermediate: [matplotlib.org/cheatsheets/handout-intermediate.pdf](https://matplotlib.org/cheatsheets/handout-intermediate.pdf)
    - tips: [matplotlib.org/cheatsheets/handout-tips.pdf](https://matplotlib.org/cheatsheets/handout-tips.pdf)

### Seaborn

- **Website**
  - The official website for Seaborn, providing information, tutorials, and resources for the Seaborn library  
  - Official site: [seaborn.pydata.org](https://seaborn.pydata.org)
- **Documentation**
  - Comprehensive guide and reference for all functionalities and features of the Seaborn library  
  - Doc: [seaborn.pydata.org/tutorial.html](https://seaborn.pydata.org/tutorial.html)
- **Source Code**
  - Over 200 contributors are currently working on Seaborn!  
  - Link: [github.com/mwaskom/seaborn](https://github.com/mwaskom/seaborn)

### Plotly

- **Website**
  - The official website for Plotly, providing information, tutorials, and resources for the Plotly library
  - Official site: [plotly.com](https://plotly.com)
- **Documentation**
  - Comprehensive guide and reference for all functionalities and features of the Plotly library
  - Doc: [plotly.com/python](https://plotly.com/python)
- **Source Code**
  - Over 200 contributors are currently working on Plotly!
  - Link: [github.com/plotly/plotly.py](https://github.com/plotly/plotly.py)

## 🤝 Contributions & Feedback

Found an issue, have a suggestion, or wish to contribute? Your input is **highly valued**.  

- 📍 All links: [**linktr.ee/mr_pylin**](https://linktr.ee/mr_pylin)
- 💬 Telegram Group: [**@python_topics**](https://t.me/python_topics)
- 📧 Email: [**amirhosseinheydari78@gmail.com**](mailto:amirhosseinheydari78@gmail.com)

I look forward to connecting with you! 🏃‍♂️

## 📄 License

This project's code is licensed under the **[Apache License 2.0](./LICENSE)**. This license grants you the freedom to **use**, **modify**, and **distribute** the code. However, any distribution of the code **must** include copies of both the [**LICENSE**](./LICENSE) and [**NOTICE**](./LICENSE) files.

### ©️ Copyright Information

- **Original Images**:
  - The images located in the [**./assets/images/original/**](./assets/images/original/) folder are licensed under the **[CC BY-ND 4.0](./assets/images/original/LICENSE)**.
  - Note: This license restricts derivative works, meaning you may share these images but cannot modify them.

- The images located in the [**./assets/images/dip_3rd/**](./assets/images/dip_3rd/) folder are licensed under the table below:  

  | Image                                                                                      | Copyright Owner                            | Address                               |
  |--------------------------------------------------------------------------------------------|--------------------------------------------|---------------------------------------|
  | [CH02_Fig0222(b)(cameraman).tif](./assets/images/dip_3rd/CH02_Fig0222(b)(cameraman).tif)    | Massachusetts Institute of Technology      | [MIT.edu](https://MIT.edu)           |
  | [CH06_Fig0638(a)(lenna_RGB).tif](./assets/images/dip_3rd/CH06_Fig0638(a)(lenna_RGB).tif)    | Public domain                              | -                                     |

- **Library-specific Images**:

  - The images located in the [**assets/images/libraries/matplotlib/**](./assets/images/libraries/matplotlib/) folder are sourced from the [**Matplotlib documentation**](https://matplotlib.org/) and are licensed under the [**Matplotlib License**](https://matplotlib.org/stable/users/license.html).
  - The images located in the [**assets/images/libraries/seaborn/**](./assets/images/libraries/seaborn/) folder are sourced from the [**Seaborn documentation**](https://seaborn.pydata.org/) and are licensed under the [**BSD 3-Clause License**](https://github.com/mwaskom/seaborn/blob/master/LICENSE).
  - The images located in the [**assets/images/libraries/plotly/**](./assets/images/libraries/plotly/) folder are sourced from the [**Plotly documentation**](https://plotly.com/) and are licensed under the [**MIT License**](https://github.com/plotly/plotly.py/blob/master/LICENSE).

- **Miscellaneous assets**:

  - The images found in [**./assets/images/misc/**](./assets/images/misc/) are modified versions of the ones listed above.
