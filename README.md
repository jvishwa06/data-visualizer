# Data Visualizer

A Streamlit app for exploring CSV files and drawing charts from them without writing code.

## How it works

1. The app lists the `.csv` files in a `data/` folder next to `app.py`. Put your CSV files there.
2. Pick a file to see a preview of its first rows.
3. Choose the X axis, the Y axis and a plot type, then press **Generate Plot**.

## Plot types

Line Plot, Bar Chart, Scatter Plot, Distribution Plot, Count Plot, Box Plot, Violin Plot, Heatmap, 3D Surface Plot, Contour Plot, Choropleth Map, Pair Plot, Regression Plot and Swarm Plot. Plots are drawn with Plotly (3D and map plots) or seaborn and matplotlib (the rest).

## Run

```bash
pip install -r requirements.txt     # streamlit, numpy, pandas, matplotlib, seaborn, plotly
mkdir data                           # add your CSV files here
streamlit run app.py
```
