
# Big Data Wrangling on your Laptop with DuckDB and Polars


> Notice this material was originally developee by Grant McDermott for the Workshops for Ukraine Series. Check out the material here 
> **Website:** https://grantmcdermott.com/duckdb-polars



### Clone of Original Repository!

This repo is a clone of [https://github.com/grantmcdermott/duckdb-polars](https://github.com/grantmcdermott/duckdb-polars). 
Now that some time has passed few of the APIs changed I did update a few function calls that no longer worked, also the data is no longer available at the old location. You can see the result of my updates on this website. The bulk of the work is still Grant's effort. 



### How to build this

My setup is

* Positron or VScode
* pyenv
* install a python version with shared library support.
```
env PYTHON_CONFIGURE_OPTS="--enable-shared" pyenv install 3.13.5
```
* create a virtualenv based on that installation
```
pyenv virtualenv 3.13.5 PyR
```
* install all required python libraries into that env and make sure it's activated in the current dir
```
pyenv local PyR
# or do pyenv activate PyR
```

* to get quarto to run with conda env, look at [this](https://thedatasavvycorner.com/blogs/08-quarto-conda-env)