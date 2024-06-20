---
date:
   created: 2023-01-01
---

# I have even older lessons, for example bokeh

## Getting Started
```
from bokeh.plotting import show, output_file, figure

x = [1,2,3,4,5]
y = [3,8,3,3,5]

output_file('index.html')

p = figure(
    title='Simple Example',
    x_axis_label='X Axis',
    y_axis_label = 'X Axis'
)

p.line(x,y, legend='Test', line_width=2)

show(p)