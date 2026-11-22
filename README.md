# Python and Data Foundations for ML — companion notebooks

Code for **Book 1** of the series *Machine Learning: From Zero to Job-Ready*.

Every code example in the book is in these notebooks, chapter by chapter, in the same order as the text. Click **Open in Colab** to run a notebook in your browser. It's free, and you don't need to install anything.

## Notebooks

| Chapter | Topic | Notebook | Run it |
|---|---|---|---|
| 1 | What is Machine Learning? | [`chapter1_what_is_ml.ipynb`](notebooks/chapter1_what_is_ml.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mayank03121994/book_python/blob/main/notebooks/chapter1_what_is_ml.ipynb) |
| 2 | Your Workspace and the Bank Data | [`chapter2_workspace_and_bank_data.ipynb`](notebooks/chapter2_workspace_and_bank_data.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mayank03121994/book_python/blob/main/notebooks/chapter2_workspace_and_bank_data.ipynb) |
| 3 | Core Python | [`chapter3_core_python.ipynb`](notebooks/chapter3_core_python.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mayank03121994/book_python/blob/main/notebooks/chapter3_core_python.ipynb) |
| 4 | Intermediate Python | [`chapter4_intermediate_python.ipynb`](notebooks/chapter4_intermediate_python.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mayank03121994/book_python/blob/main/notebooks/chapter4_intermediate_python.ipynb) |
| 5 | Advanced Python | [`chapter5_advanced_python.ipynb`](notebooks/chapter5_advanced_python.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mayank03121994/book_python/blob/main/notebooks/chapter5_advanced_python.ipynb) |
| 6 | Coding Practice | [`chapter6_coding_practice.ipynb`](notebooks/chapter6_coding_practice.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mayank03121994/book_python/blob/main/notebooks/chapter6_coding_practice.ipynb) |
| 7 | NumPy and pandas | [`chapter7_numpy_and_pandas.ipynb`](notebooks/chapter7_numpy_and_pandas.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mayank03121994/book_python/blob/main/notebooks/chapter7_numpy_and_pandas.ipynb) |
| 8 | Data Visualisation | [`chapter8_data_visualisation.ipynb`](notebooks/chapter8_data_visualisation.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mayank03121994/book_python/blob/main/notebooks/chapter8_data_visualisation.ipynb) |
| 9 | The Maths You Need | [`chapter9_maths_you_need.ipynb`](notebooks/chapter9_maths_you_need.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mayank03121994/book_python/blob/main/notebooks/chapter9_maths_you_need.ipynb) |
| 10 | EDA and Data Cleaning | [`chapter10_eda_and_cleaning.ipynb`](notebooks/chapter10_eda_and_cleaning.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mayank03121994/book_python/blob/main/notebooks/chapter10_eda_and_cleaning.ipynb) |
| — | Solutions to all exercises | [`book1_solutions.ipynb`](notebooks/book1_solutions.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mayank03121994/book_python/blob/main/notebooks/book1_solutions.ipynb) |

## How to use them

1. Click **Open in Colab** next to the chapter you are reading. You need a free Google account.
2. In Colab, choose **File → Save a copy in Drive**, so your changes are kept.
3. From Chapter 7 onwards, run the **set-up cell** at the top first. It downloads the bank data with `ucimlrepo`.
4. If you see an error such as `NameError: name 'bank' is not defined`, a cell was skipped. Use **Runtime → Run all**.

The notebooks are saved without outputs, so you see each result appear when you run the cell. The book prints the outputs you should expect. Small differences, such as a warning worded differently or a chart in slightly different colours, can come from newer library versions.

To run the notebooks on your own computer instead, install Python and Jupyter (for example with [Anaconda](https://www.anaconda.com)), then:

```bash
git clone https://github.com/mayank03121994/book_python.git
cd book_python/notebooks
pip install numpy pandas matplotlib seaborn scipy scikit-learn ucimlrepo
jupyter notebook
```

## The dataset

All chapters use the **Bank Marketing** dataset from the UCI Machine Learning Repository: 45,211 phone calls made by a Portuguese bank, and whether each customer subscribed to a term deposit. Amounts are in euros.

- Dataset page: <https://archive.ics.uci.edu/dataset/222/bank+marketing>
- Citation: Moro, S., Rita, P. and Cortez, P. (2014). *Bank Marketing* [Dataset]. UCI Machine Learning Repository. <https://doi.org/10.24432/C5K306>
- Paper: Moro, S., Cortez, P. and Rita, P. (2014). A data-driven approach to predict the success of bank telemarketing. *Decision Support Systems*, 62, 22–31. <https://doi.org/10.1016/j.dss.2014.03.001>

The dataset is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

## Found a problem?

If a notebook stops working (for example after a library update), please [open an issue](https://github.com/mayank03121994/book_python/issues) with the chapter, the cell and the error message.

## Licence

© 2026. The notebooks are free to use and modify for personal learning. The book's text is not included here.
