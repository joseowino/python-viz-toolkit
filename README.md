# 📊 Python Viz Toolkit

A hands-on introduction to data visualization in Python using **Pandas**, **Matplotlib**, and **Plotly** — covering everything from quick exploratory plots to rich interactive dashboards.

> **Repo:** [https://github.com/joseowino/python-viz-toolkit](https://github.com/joseowino/python-viz-toolkit)

---

## 📌 Overview

Understanding your data visually is one of the most important skills in data science. This project walks through the three most popular Python visualization libraries and when to use each:

| Library | Best For |
|---|---|
| **Pandas `.plot()`** | Quick, exploratory plots directly from DataFrames |
| **Matplotlib** | Custom, fine-grained, publication-ready plots |
| **Plotly** | Interactive, web-ready, and dynamic visualizations |

---

## 🗂️ Project Structure

```
python-viz-toolkit/
│
├── ex00_setup/               # Environment setup
├── ex01_pandas_bar/          # Pandas bar plot
├── ex02_pandas_scatter/      # Pandas scatter plot
├── ex03_matplotlib_basic/    # Matplotlib line + scatter
├── ex04_matplotlib_twinx/    # Matplotlib dual-axis plot
├── ex05_matplotlib_subplots/ # Matplotlib subplots grid
├── ex06_plotly_line/         # Plotly Express & graph_objects line chart
├── ex07_plotly_boxplot/      # Plotly box plots
│
├── requirements.txt
└── README.md
```

---

## ⚙️ Setup

### Prerequisites
- Python >= 3.9
- `pip` or `conda`

### Installation

**Using `virtualenv`:**
```bash
python -m venv ex00
source ex00/bin/activate        # On Windows: ex00\Scripts\activate
pip install -r requirements.txt
```

**Using `conda`:**
```bash
conda create -n ex00 python=3.11
conda activate ex00
pip install -r requirements.txt
```

### Required Libraries

```txt
pandas
numpy
matplotlib
plotly
jupyter
```

Or install directly:
```bash
pip install pandas numpy matplotlib plotly jupyter
```

### Launch Jupyter
```bash
jupyter notebook
```

---

## 🧪 Exercises

### Exercise 0 — Environment Setup
Set up a virtual environment named `ex00` with Python >= 3.9 and all required libraries.

---

### Exercise 1 — Pandas Bar Plot
Create a bar plot from a small DataFrame of people with attributes like age, state, and number of pets.

**Key concepts:** `df.plot(kind='bar')`, titles, legends, axis labels.

---

### Exercise 2 — Pandas Scatter Plot
Plot age vs. number of children to explore potential correlations.

**Key concepts:** `df.plot(kind='scatter')`, axis labels, visual pattern recognition.

---

### Exercise 3 — Matplotlib Line & Scatter
Reproduce a styled plot with a red dash-dot line and blue circles.

**Key concepts:** `plt.plot()`, line styles, marker styles, axis limits.

---

### Exercise 4 — Matplotlib Dual Axis (`twinx`)
Plot two datasets with different value ranges on the same figure using a secondary y-axis.

**Key concepts:** `ax.twinx()`, multiple axes, colour-coded lines.

---

### Exercise 5 — Matplotlib Subplots
Generate a 2×3 grid of subplots using a `for` loop.

**Key concepts:** `plt.subplots()`, `hspace`/`wspace`, `ax.text()`, subplot titles.

---

### Exercise 6 — Plotly Line Chart
Plot a simulated company stock price as an interactive line chart — first with **Plotly Express**, then with **`plotly.graph_objects`**.

**Key concepts:** `px.line()`, `go.Figure()`, `go.Scatter()`, interactivity.

---

### Exercise 7 — Plotly Box Plots
Compare three shifted normal distributions side-by-side as box plots.

**Key concepts:** `go.Box()`, quartiles, legends, distribution comparison.

---

## 📚 Resources

- [Pandas Visualization Docs](https://pandas.pydata.org/docs/user_guide/visualization.html)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [Plotly Python Documentation](https://plotly.com/python/)
- [Plotly Express Overview](https://plotly.com/python/plotly-express/)
- [Plotly Box Plots](https://plotly.com/python/box-plots/)

---

## 🤝 Contributing

Pull requests are welcome! If you have suggestions for improving existing exercises or want to add new ones, feel free to open an issue or submit a PR.

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).