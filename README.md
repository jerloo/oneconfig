
# OneCofnig

A config lib for python.

## Installation

```console
pip install oneconfig
```

## Usage

```python

from oneconfig.cores import Configuration

class MyConfig(Configuration):
    port = 8080
    domain = "localhost"
    
myconfig = MyConfig()
myconfig.add_file_by_prefix("appsettings")

```

## LICENSE

The MIT License (MIT)

Copyright (c) 2018 jeremaihloo
