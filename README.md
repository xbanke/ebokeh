# ebokeh
ebokeh is an enhanced bokeh that can plot line, circle and so on with pd.DataFrame or list of soure names straightly. So you can plot like this:

fig = figure('Fig')

fig.line(df)

or 

fig = figure('Fig')

fig.line('x', ['y1', 'y2', 'y3'], source=source)

or

fig = figure('Fig')

fig.line('x', 'y1,y2,y3', source=source)
