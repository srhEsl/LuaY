# LuaY
LuaY is built on LuaU, but it makes every function 3 letters.
## How do I use LuaY?
### Using external Lua injector with loadstring & game:HttpGet compatibility
Put this at the start of your script:   
```lua
loadstring(game:HttpGet("https://github.com/srhEsl/LuaY/raw/main/luayloader.lua"))()
--script below here
```
### Using Roblox Lua environment with loadstring & HttpService enabled
Put this at the start of your script:   
```lua
loadstring(game:GetService("HttpService"):GetAsync("https://github.com/srhEsl/LuaY/raw/main/luayloader.lua"))()
--script below here
```
### Other
Copy the contents of the [luayloader.lua](https://github.com/srhEsl/LuaY/raw/main/luayloader.lua) file to the start of your script.
## Changelogs
### V0.0.2
Added the functions:    
why
### V0.0.1
Changed the functions:   
print - say   
tostring - str   
warn - wrn   
pcall - ptcall    
error - err
