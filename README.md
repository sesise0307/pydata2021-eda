# [PyData Global 2021] Know Your Data First: An Introduction to Exploratory Data Analysis

This is a hands-on tutorial that introduces comprehensive
Exploratory Data Analysis (EDA) techniques to have better understandings
about your data before doing serious tasks such as machine-learning
or deep-learning.

## Target Audience

- Student who wants to be a data scientist
- Junior data scientist
- Machine-learning researcher

## Prerequisite

- Some experiences with
  - `Python`
  - `Pandas`
  - `Matplotlib`
  - `Jupyter Notebook` (or similar)
- GitHub & Google accounts
- `Fork` this repo then go to: https://colab.research.google.com/github/{your_github_id}/pydata2021-eda/

## Outline

1. [Introduction](slides.pdf)
2. [Data loading and preprocessing](notebook/2_Data_Loading_and_Preprocessing.ipynb)
    - Loading a *csv* file
    - Merging many *csv* files
    - Essential check list: Missing Values, #Samples, Column Names, Unique Values, etc.
    - Preprocessing: fillna, dropna, feature engineering, etc.
    - `sidetable`
3. [Statistical Visualizations](notebook/3_Statistical_Visualizations.ipynb)
    1. `matplotlib`: basic building block, essential for fine-tuning
        - lineplot, scatterplot, heatmap, etc
    2. Visualization with *pandas*
    3. `seaborn`: handy `matplotlib` wrapper for statistical visualization
        - pairgrid, stripplot, distplot, barplot, violinplot, etc.
        - tidy data
        - fine-tuning: seaborn then *matplotlib*
4. (Easy Enough) [Interactive Visualizations](notebook/4_Interactive_Visualization.ipynb)
    1. `ipywidgets`
    2. `plot.ly` and `plot.ly` express
    3. `bokeh`
    4. `altair`
5. [Automatic EDA Report](notebook/5_Automatic_EDA.ipynb)
   1. `dtale`
   2. `pandas-profiling`
   3. `sweetviz`
   4. `autoviz`
6. Wrap-up and Some Tips

## Contact

Sin-seok SEO @Safran Tech, Safran SA

- [Webpage](https://sesise.webflow.io/)
- [LinkedIn](https://www.linkedin.com/in/sin-seok-seo-9a470949/)
- [GitHub](https://github.com/sesise0307)
