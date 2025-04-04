
# GIFgraph
------------




Version: 0.1.2 || Author: Henry Taylor || Email: henrysrtaylor@gmail.com

------------



## How to install:

You can install with PyPi from your command terminal: 
>*pip install GIFgraph*

## How To Use:
GIFgraph is a simple libary to help create animated data driven visuals. 

The library was created and imagined to be used within single cells as part of a data science/ analytics solution and therefore works best in conjunction with Jupyter notebooks.

Version 0.1.2 includes support for four types of chart: scatter (GG_scatter), pie (GG_pie), bar (GG_bar), and line (GG_line). Upon calling these functions with appropriate arguments, a window will appear displaying the animation. A user can find these animations, along with individual frames on their desktop (or a user specified path) under GIfgraph. All arguments are specified for each function in the following section.

Please note: all testing is performed on Windows and therefore functionality may not be fully supported for Mac and Linux systems. 

## Arguments: 
Arguments for each functioin can be found here, and also accessed within code by calling help(function). 

GG_bar:

	Parameters: 
                x - x-axis data.
                y - y-axis data.
                xname - x-axis name.
                yname - y-axis name.
                name - Title of GIF.
                step - How many data points to be plotted per frame.
                size - Size of GIF.
                dpi - Dots Per Inch.
                xrotation - Rotation of x-axis.
                milsec - miliseconds between each frame.
                loop - Loop type, 0 is infinite, loop > 0 sets loop for that amount. This only applies to saved GIF. If show_GIF=True then GIF that displays will be infinite. 
                file_path - Folder where file structure will be created.
                show_GIF - Bool, True or False.


GG_line:

	Parameters: 
                x - x-axis data.
                y - y-axis data.
                xname - x-axis name.
                yname - y-axis name.
                name - Title of GIF.
                step - How many data points to be plotted per frame.
                size - Size of GIF.
                dpi - Dots Per Inch.
                xrotation - Rotation of x-axis.
                milsec - miliseconds between each frame.
                loop - Loop type, 0 is infinite, loop > 0 sets loop for that amount. This only applies to saved GIF. If show_GIF=True then GIF that displays will be infinite. 
                file_path - Folder where file structure will be created.
                show_GIF - Bool, True or False.

GG_scatter:

	Parameters: 
                x - x-axis data.
                y - y-axis data.
                xname - x-axis name.
                yname - y-axis name.
                name - Title of GIF.
                step - How many data points to be plotted per frame.
                size - Size of GIF.
                dpi - Dots Per Inch.
                xrotation - Rotation of x-axis.
                milsec - miliseconds between each frame.
                loop - Loop type, 0 is infinite, loop > 0 sets loop for that amount. This only applies to saved GIF. If show_GIF=True then GIF that displays will be infinite. 
                file_path - Folder where file structure will be created.
                show_GIF - Bool, True or False.


GG_pie: 

	Parameters: 
                x - x-axis data.
                y - y-axis data.
                name - Title of GIF.
                Explode - Distance of pie segments from each other.
                step - How many data points to be plotted per frame.
                autopct - Pie chart percentages. Add string based on formatting or None.
                autopct_color - Color of data labels. 
                label_color - Color of text labels ~ 'y'. 
                colors_list - list of colors to use for each pie segment. Accepts hex, and color names. Ensure number of colors >= number segments. 
                legend - displays legend on chart.
                shadow - displays shadow under pie.
                size - Size of GIF.
                dpi - Dots Per Inch.
                milsec - miliseconds between each frame.
                loop - Loop type, 0 is infinite, loop > 0 sets loop for that amount. This only applies to saved GIF. If show_GIF=True then GIF that displays will be infinite. 
                file_path - Folder where file structure will be created.
                show_GIF - Bool, True or False.
