![Texto img](kamelid-low-resolution-logo-color-on-transparent-background.png)

### `kamelid` is an orchestration framework to create customized AI powered chatbots

- Very easy to use [Quickstart](www.google.com)
- Integration with lots of [Large Language Models](www.google.com)
- Integration with top [Chat Interfaces](www.google.com)

## Usage

#### TL;DR;
```python
from kamelid import AIChat

mychat = AIChat(
    engine = {'llm':'LLaMA2'},
    platform = {'api':'WhatsApp','number':'my_number'}
    
mychat.deploy()
```

## Installation

1. Install main dependencies 
```bash
pip install kamelid
``` 
1. [Engine dependencies](www.google.com)   (Example for `OpenAI`)
```bash
pip install openai
export OPENAI_API_KEY="..."
``` 
1. [Platform dependencies](www.google.com) (Example for `WhatsApp`)
```bash
git clone https://github.com/Neurotech-HQ/heyoo
cd heyoo
python setup.py install 
```

Note that you need an `OPENAI_API_KEY` to use this script. The library needs to be configured with your account's secret key which is available on the [website](https://platform.openai.com/account/api-keys).
