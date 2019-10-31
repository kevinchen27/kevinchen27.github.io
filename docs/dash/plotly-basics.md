## Install plotly 

Basic plotly gives us idea of Dash syntax and documentation
<br>
`pip install plotly==4.2.1`

## Import plotly

`import plotly.offline as pyo`
`import plotly.graph_objs as go`

## Scatter plots

Data must first be in a list
<br>
data = [go.Scatter(x= <list of values for x-axis>,
    y =<list of values for y-axis>,
    mode = 'markers', 
    marker = dict(size = 12,
    color = "rgb(51,204,153)",
    symbol = "pentagon",
    line = dict(width = 2)
    ))]
