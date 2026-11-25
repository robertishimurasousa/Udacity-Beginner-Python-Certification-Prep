# Beginner Python PCEP™ Certification Prep

This repository contains the exercises and starter project for Beginner Python PCEP™ Certification Prep, Course 2 of Udacity’s AI Programming with Python Nanodegree Program. The course builds the Python skills used in later data analysis and machine learning coursework. [Nanodegree curriculum](https://www.udacity.com/course/ai-programming-python-nanodegree--nd089) · [Course outline](https://www.udacity.com/course/beginner-python-pcep-certification-prep--cd13568)

## Lessons

| Lesson | What you practice |
| --- | --- |
| [1. Python Programming Fundamentals](Exercises/L1-Python%20Programming%20Fundamentals/) | Jupyter, variables, basic types, and introductory Python code |
| [2. Python Boolean Logic and Numeric Operators](Exercises/L2-Python%20Boolean%20Logic%20and%20Numeric%20Operators/) | String and arithmetic operations, comparisons, and type conversions |
| [3. Python Control Flow and Loops](Exercises/L3-Python%20Control%20Flow%20and%20Loops/) | Loops, `range()`, `break`, and `continue` |
| [4. Python Data Structures](Exercises/L4-Python%20Data%20Structures/) | Lists, tuples, indexing, slicing, and string methods |
| [5. Python Functions](Exercises/L5-Python%20Functions/) | Parameters, default values, return values, and generators |
| [6. Python Exceptions](Exercises/L6-Python%20Exceptions/) | Handling and propagating exceptions with `try` and `except` |

Start with an `Exercise1.ipynb` or `Exercise2.ipynb` notebook and run its cells in order. Use the matching `_Solutions.ipynb` notebook to compare your work.

## Run the notebooks locally

Use a Python 3 kernel with Jupyter or PyCharm. The lesson exercises use Python’s standard library. On macOS or Linux, run these commands from the repository root to launch Jupyter. If `.venv` already exists, start with the second command.

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install notebook
jupyter notebook
```

Open the first exercise and work through the lessons in order. In PyCharm, select the project’s `.venv/bin/python` interpreter for your notebook kernel. [First exercise](Exercises/L1-Python%20Programming%20Fundamentals/Exercise1.ipynb)

## Course project

In **A Data-Driven Approach to AI and Python**, you stream samples of electronics reviews and product metadata from Amazon Reviews 2023, explore and filter the data with pandas, then visualize prices and ratings with Matplotlib and Seaborn. The starter notebook guides you through the workflow and includes the code cells and reflection questions to complete. [Project notebook](Project/Udacity%20-%20PCEP%20Project.ipynb) · [Amazon Reviews 2023 dataset](https://huggingface.co/datasets/McAuley-Lab/Amazon-Reviews-2023)

Use the environment and package versions provided in the Udacity classroom when available. Part 1 of the notebook lists the project dependencies (`datasets`, `pandas`, `matplotlib`, `seaborn`, and `pyarrow`). For local runs, the starter uses a legacy Hugging Face loader with `trust_remote_code`. Hugging Face removed support for that option and for dataset scripts in `datasets` 4.0. [Hugging Face release notes](https://github.com/huggingface/datasets/releases/tag/4.0.0)

The notebook’s submission checklist includes the executed notebook with cell outputs, `user_inputs.txt` with your reflection answers, and the `top_products.csv` and `top_products.parquet` exports. Use the Udacity classroom for the submission rubric.

## Security and license

Use the private reporting process for repository security issues. [Security policy](SECURITY.md)

See the repository license for the terms that apply to Udacity educational content. [License](LICENSE.txt)
