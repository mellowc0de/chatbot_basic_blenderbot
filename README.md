### chatbot_basic_blenderbot

#### Setting up the Virtualenv

```python

pip3 install virtualenv
virtualenv my_env
source my_env/bin/activate
```

#### Installing Required Packages

```python

python3.11 -m pip install transformers==4.38.2
python3.11 -m pip install torch==2.2.1
```

#### Adding Required Packages to the App

```python
import json
from flask import Flask, request
from flask_cors import CORS
from transformers import AutoModelForSeq2SeqLM
from transformers import AutoTokenizer
```
