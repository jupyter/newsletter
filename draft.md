#Jupyter/IPython newsletter for Date. 


# Misc links to write about:


## Prompt toolkit integration in IPython master:

https://github.com/ipython/ipython/pull/9118

please try with 

```
python3 -m IPython.terminal.ptshell
```

It will likely become the default in the future.


## nbstripout

People keep reinventing the wheel and write their own [git
filter](https://github.com/adrn/DropOutput/issues/1) that clean-up outputs of
notebook in VCS. While we think that output should be stored – for example to
be rendered ion nbviewer – we understand the needs for such filters:


Nice to see Jovyans getting together, and write a tool
that can easily be installed/uninstalled to add git hooks:

    https://github.com/kynan/nbstripout

```
$ pip install nbstripout
$ cd git/repository
$ nbstripout install
```


