# World-Minimum-Wage-and-USA-State-Expenditure-Choropleth-Maps
A showcase of Choropleth Maps using World Minimum Wage and USA State Expenditure data

Dataset: KFF, OECD (uploaded to the repository)

The objective was to showcase the wonderful choropleth maps and its applicability in data visualization.
Python was used to read, clean, and store two CSV files and NumPy, Pandas, and Plotly were used to provide data visualization.

# Install
pip install numpy | conda install numpy

pip install pandas | conda install pandas

pip install plotly 

pip install chart-studio

# Import
import chart_studio.plotly as py

import plotly.graph_objs as go 

from plotly.offline import download_plotlyjs, init_notebook_mode, plot, iplot

init_notebook_mode(connected=True) 

import pandas as pd
