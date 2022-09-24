## Python3 Virtualenv Setup

##### Requirements
* Python 3
* Pip 3

```bash
$ brew install python3
```

Pip3 is installed with Python3

##### Installation
To install virtualenv via pip run:
```bash
$ pip3 install virtualenv
```

##### Usage
Creation of virtualenv:
```bash
$ virtualenv -p python3 <desired-path>
```

Activate the virtualenv:
```bash
$ source <desired-path>/bin/activate
```

Deactivate the virtualenv:
```bash
$ deactivate
```

Export requirements.txt:
```bash
$ python3 -m pip freeze >> requirements.txt
```

Install dependency form requirements.txt:
```bash
$ python3 -m pip install -r requirements.txt
```


[About Virtualenv](https://virtualenv.pypa.io/en/stable/)
