# Data-Visualisation-with-Python

%matplotlib inline  ##This is a Magic function
.
.
.
.

# A magic function starts with % Matplotlib, and to enforce plots to be rendered within the browser, you pass in inline as the backend. Matplotlib has a number of different backends available. One limitation of this backend is that you cannot modify a figure once it's rendered. So after rendering the above figure, there is no way for us to add, for example, a figure title or label its axes. You will need to generate a new plot and add a title and the axes labels before calling the show function. 


%matplotlib notebook
##A backend that overcomes this limitation is the notebook backend. With the notebook backend in place, if a plt function is called, it checks if an active figure exists, and any functions you call will be applied to this active figure. If a figure does not exist, it renders a new figure. 


#So when we call the plt.plot function to plot a circular mark at position (5, 5), the backend checks if an active figure exists. Since there isn't an active figure, it generates a figure and adds a circular mark to position (5, 5). And what is beautiful about this back end is that now we can easily add a title for example or labels to the axes after the plot was rendered, without the need to regenerate the figure.
