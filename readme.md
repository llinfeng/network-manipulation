With a tiny bit of Python knowledge and the help of popular network modules
(well, one of them is enough), we can import and derive network related
metrics. For now, this repo aims at getting people started when they have
"handy" network data :)


# Links for documentation
* [Get started with python-igraph](https://igraph.org/python/)
* [Tutorial for NetwrokX](https://networkx.org/documentation/stable/tutorial.html)

`python-igraph` is based on `igraph`, with implmenttaion in R, C and Python.
The `igraph` project has [received funding from Facebook in 2019 or
so](https://chanzuckerberg.com/eoss/proposals/providing-a-solid-foundation-for-network-analysis/).
Since the core algorithms are optmized for computing in C, the `python-igraph`
acts as a wrapper layer, making the initial setup a bit more hectic.

The coeebase for `networkx` is solely written in Python. For that, it setup
process can be a bit more "flexible" and intuitive.

To carry out the "**setup process**", we shall take the raw data and parse into
proper data structure in Python. Then, we shall construct a "Network object" using
either package.

# Overview


## Credits
The `NetworkX(standalone).ipynb` is copied from [GitHub - jdwittenauer/ipython-notebooks: A
collection of IPython notebooks covering various
topics.](https://github.com/jdwittenauer/ipython-notebooks).

The `BuildNetwork_pyhton-igraph.ipynb` notebook is converted from an old setup
script drafted by Linfeng.
