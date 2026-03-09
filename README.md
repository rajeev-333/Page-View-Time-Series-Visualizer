# Page View Time Series Visualizer

A Python project built as part of the **FreeCodeCamp Data Analysis with Python** certification.

## Description
Visualizes time series data of daily page views on the freeCodeCamp.org forum
from **May 2016 to December 2019** using Pandas, Matplotlib, and Seaborn.
Produces three charts to identify growth trends and seasonal patterns.

## Charts Produced

| Chart | File | Description |
|---|---|---|
| Line Plot | `line_plot.png` | Daily page views over the full period |
| Bar Plot | `bar_plot.png` | Average monthly page views grouped by year |
| Box Plot | `box_plot.png` | Year-wise and month-wise distribution of page views |

## How to Run

### Install dependencies
```bash
pip install matplotlib seaborn pandas numpy
```
### Run the project
```bash
python main.py
```
## Project Structure
```
├── time_series_visualizer.py  # Main solution file
├── fcc-forum-pageviews.csv    # Dataset (freeCodeCamp forum page views)
├── main.py                    # Run and test the solution
├── test_module.py             # Unit tests (do not modify)
├── examples/                  # Reference chart images
├── line_plot.png              # Generated line chart
├── bar_plot.png               # Generated bar chart
├── box_plot.png               # Generated box plots
└── README.md
```
## Technologies Used
* Python 3

* Pandas

* Matplotlib

* Seaborn
