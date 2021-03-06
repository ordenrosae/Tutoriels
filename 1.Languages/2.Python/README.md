# :m: Python

## :one: Installation de la machine virtuelle Python

:pushpin: Par un Package Manager

:bulb: Windows

```
PS > choco install python3 --pre
```

:apple: MacOS 

### Install @3.8

```
$ brew install python@3.8
```

* Set the ENV Variables

```
$ echo 'export PATH="/usr/local/Cellar/python@3.8/3.8.1/libexec/bin:$PATH"' >> ~/.zshrc
# or for Bash
$ echo 'export PATH="/usr/local/Cellar/python@3.8/3.8.1/libexec/bin:$PATH"' >> ~/.bashrc
```

```
$ brew switch python@3.8 3.8.1
```

:pushpin: Manuellement

* Python 3.7.4 :  https://www.python.org/downloads/

### Pour tester l'installation
```
$ python --version
Python 3.7.4
```

## :two: Installation des outils d'édition

[Anaconda](Anaconda.md)

[IDE](IDE.md)



# References:

https://www.python.org/about/gettingstarted/

https://kite.com/blog/python/functional-programming/ (Programmation Fonctionelle)

https://stackoverflow.com/questions/37117571/where-does-anaconda-python-install-on-windows (Uninstall manually installed Anaconda)

https://opensource.com/article/19/5/python-3-default-mac
