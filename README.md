# Analysis of Kaggle Datasets

A Python data analysis project that explores a catalog of **13,000+ Kaggle datasets** (creators, categories, downloads, votes and views) using Pandas, NumPy, Matplotlib and Seaborn.

## What this project does

- Loads the Kaggle datasets metadata (`all_kaggle_datasets.csv`) and inspects its shape, data types and missing values
- Cleans missing values
- Studies correlations between numeric columns with a Seaborn heatmap
- Finds unique dataset creators, owners and dataset URLs
- Counts how many datasets each creator has published
- Counts datasets per category and lists categories without duplicates
- Ranks the **top 10** by download count, vote count and view count
- Builds **word clouds** for dataset categories and creators

## Tech stack

| Area | Tools |
| --- | --- |
| Language | Python |
| Data analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn, WordCloud |
| Text handling | NLTK, regular expressions (`re`) |
| Environment | Jupyter Notebook |

## Project files

| File | Description |
| --- | --- |
| `final_kaggle-Copy1.ipynb` | Main analysis notebook |
| `all_kaggle_datasets.csv` | Dataset used in the analysis (if not included, see the note below) |

## How to run

1. Install the libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn nltk wordcloud notebook
   ```

2. Place `all_kaggle_datasets.csv` in the same folder as the notebook.

3. In the notebook, change the file path in the data loading cell to:

   ```python
   kaggle = pd.read_csv('all_kaggle_datasets.csv')
   ```

4. Start Jupyter and run all cells:

   ```bash
   jupyter notebook
   ```

> **Note:** The original notebook reads the file from a local `Downloads/` folder, so the path must be updated as shown in step 3 before running it elsewhere.

## Author

**Jeevika Kaliappan**
B.Tech Information Technology
[LinkedIn](https://www.linkedin.com/in/jeevika-kaliappan-95564937a) | jeevikakaliappan@gmail.com
