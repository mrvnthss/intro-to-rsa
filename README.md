# intro-to-rsa

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mrvnthss/intro-to-rsa/blob/main/intro-to-rsa.ipynb)
[![Jupyter](https://img.shields.io/badge/Jupyter-Lab-F37626.svg?style=flat&logo=Jupyter)](https://jupyterlab.readthedocs.io/en/stable)
[![Python](https://img.shields.io/badge/Python-3.11-3776AB.svg?style=flat&logo=python&logoColor=white)](https://www.python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch_2.5.1-EE4C2C?logo=pytorch&logoColor=white)](https://pytorch.org/get-started/locally/)
[![GitHub License](https://img.shields.io/github/license/mrvnthss/deep-learning-with-dobble?color=ad2317)](https://www.gnu.org/licenses/gpl-3.0.html.en)

## Getting Started

To get started right away, simply open the notebook in [Google Colab](https://colab.research.google.com/github/mrvnthss/intro-to-rsa/blob/main/intro-to-rsa.ipynb). Alternatively, follow these steps to clone the repository and run the project on your local machine.

### Prerequisites

- Python 3.11 installed on your machine.
- Operating system: Unix/macOS

### Clone the Repository

1. Open a terminal or command prompt on your local machine.

2. Clone the repository using `git`:

```
git clone https://github.com/mrvnthss/intro-to-rsa
cd intro-to-rsa
```

### Set up a Virtual Environment (Optional but Recommended)

Before you begin, make sure that `pip` is installed on your system. `pip` is a package manager for Python, and it's usually included by default when you install Python. To ensure that `pip` is installed, run the following commands:

```
python3 -m pip install --user --upgrade pip
python3 -m pip --version
```

Setting up a virtual environment helps isolate project dependencies. If you don't have `virtualenv` installed, you can install it using:

```
python3 -m pip install --user virtualenv
```

Create and activate a virtual environment:

```
python3 -m venv .venv
source .venv/bin/activate
```

### Install Dependencies

All the dependencies that are required to execute the notebooks in this repository are listed in the [requirements.txt](requirements.txt) file. Installing these is a breeze. Simply issue the following command after you have set up your virtual environment:

```
pip install -r requirements.txt
```

### Start JupyterLab

To start [JupyterLab](https://jupyter.org), simply run the following command inside your activated virtual environment:

```
juypter lab
```

## License

This project is open source and available under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html) (GPLv3). The GPLv3 is a copyleft license that allows for the free distribution, modification, and use of this software, ensuring that all derivatives of this work are also available under the same license. Here’s a summary of the license’s main points:

- **Freedom to Use**: You are free to use this software for any purpose, including commercial applications, in accordance with the license terms.

- **Freedom to Modify**: You can modify the source code of this software, allowing you to tailor it to your needs or improve upon it. Your modifications must also be licensed under GPLv3.

- **Freedom to Share**: You can distribute this software freely, whether in its original form or with your modifications, as long as you also make the source code available under the same license terms.

- **Share Alike**: If you distribute modified versions of this software, you must also do so under the GPLv3, ensuring that all derivatives remain free and open source under the same terms.

- **Attribution and Notices**: When distributing or modifying the project's software, you must retain all copyright notices and author attributions found in the original work, as well as provide notices that you have modified the work. This ensures transparency and respects the original creators' contributions.

- **No Additional Restrictions**: You may not impose any further restrictions on the recipients' exercise of the rights granted under the license. This includes not using legal terms or technological measures that legally restrict others from doing anything the license permits.

For more detailed information, please review the full [LICENSE](LICENSE) text. By using, distributing, or contributing to this project, you agree to abide by the terms of the GNU GPLv3.
