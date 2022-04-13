## Rose bot example plugin format here :
You can create your own custom plugin useing this format or use any [pyrogram](http://pyrogram.org) method !


```
from Rose import app
from Rose.utils.commands import *

@app.on_message(command("test"))
async def plug(_, message):
    Kutty_Angel_Bot_Group = await message.reply_text(text="Hello I am Kutty Angel"
    )
    supun = """
I'm a group management bot with some useful features.
@Kutty_Angel_Bot_Group    
    """
    await KuttyAngelXPlus_bot.edit_text(joedusky)

__MODULE__ = "test"
__HELP__ = """  
/test - test cmd here
"""
```

