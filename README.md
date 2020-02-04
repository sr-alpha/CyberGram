#### > CyberGram <
Telegram bot library and platform of chats.  

view [Docs](https://tele.readthedocs.io)  
[GitHub](https://github.com/sr-alpha/CyberGram)  
[pypi](https://pypi.org/project/cybergram)  
##### Installation – CyberGram

requires python 3.5+ to run.

`pip3 install CyberGram`

```python 
from cybergram import *


@bot('text')
def echo(mssg):
    mssg.reply(mssg.text)


account('YOUR-TOKEN')
bot_run()

```
