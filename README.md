# Explorations in ServiceX

Exploring using [ServiceX](https://github.com/ssl-hep/ServiceX) as a tool for performing studies on ATLAS

## Setup

First in a Python 3 virtual environment install the dependencies

```
python -m pip install -r requirements.txt
python -m pip install -r dev-requirements.txt
```

Then, after getting Globus permissions for ServiceX use, put the resulting YAML
file in a `.servicex` config file and place it in a location that ServiceX can
find it.
ServiceX will look in `$HOME`, so (assuming you created a file called `atlas-servicex.yaml`)
you can do the following

```
cp atlas-servicex.yaml ~/.servicex
```
