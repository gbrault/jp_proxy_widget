jp_proxy_widget
===============================

Generic Jupyter/IPython widget implementation that will support many types of javascript libraries and interactions.

Installation
------------

To install use pip:

    $ pip install jp_proxy_widget
    $ jupyter nbextension enable --py --sys-prefix jp_proxy_widget


For a development installation (requires npm),

    $ git clone https://github.com/AaronWatters/jp_proxy_widget.git
    $ cd jp_proxy_widget

Then optionally if you want a clean build use

    $ git clean -f -d

to remove all build artifacts from a development tree (after changing the javascript).

    $ pip install -e .
    $ jupyter nbextension install --py --symlink --sys-prefix jp_proxy_widget
    $ jupyter nbextension enable --py --sys-prefix jp_proxy_widget

Use

    $ git clean

to remove all build artifacts from a development tree (after changing the javascript).
