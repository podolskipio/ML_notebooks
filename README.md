# How to use this repo

```
git clone https://github.com/podolskipio/sus.git
cd sus/
```

## Conda


```
$ conda env create -f environment.yml
$ conda activate sus_notebooks
```

## Pip and virtualenv

```
$ sudo apt-get update
$ sudo apt-get install python3 python3-pip
```

```
$ python3 -m pip install --user --upgrade pip
```

```
$ python3 -m pip install --user --upgrade virtualenv
$ python3 -m virtualenv -p `which python3` env
```

```
$ source ./env/bin/activate
$ python3 -m pip install --upgrade -r requirements.txt
```

## Run notebooks
```
$ jupyter notebook
```
