# Api-TGBot

A simple telegram-bot wtitten in LUA based on [CeWeR bot](https://github.com/CeWeR/test001)

# Installation


```bash
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev
 

``` 
`sudo apt-get install lua-socket` & `sudo apt-get install lua-sec`


Clone the bot

```
git clone https://github.com/CeWeR/Api.git
cd Api

```

Then install bot using

`lua bot.lua`

bot token in bot.lua (config part)



```lua

local bot_api_key = "" -- token
local BASE_URL = "https://api.telegram.org/bot"..bot_api_key
local BASE_FOLDER = "" -- do not set this
```

And enter your telegram-id in admins table in [bot.lua](https://github.com/CeWeR/api/blob/master/bot.lua#L19)
```lua
local var = false
  local admins = {153545455}-- put your id here
  for k,v in pairs(admins) do

```

Save bot.lua

```
bash launch.sh install && bash launch.sh
``` 

for Start the bot
