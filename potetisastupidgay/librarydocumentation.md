# putting the library in ur script
```lua
local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/railme37509124/tabiForBss/refs/heads/main/potetisastupidgay/uilibrary.lua", true))()
```
# make window
```lua
local window = library:New("Your Title") 2nd and 3rd arguments can be used for colors (primrary and secondary)
```
# make tab
```lua
local tab = window:Tab("Tab")
```
# make folder
```lua
local folder = tab:Folder("Your Folder")
```
# make toggle
```lua
local toggle = folder:Toggle("Toggle", function(state)
  print(state) -- true/false
end)
```
# make button
```lua
local button = folder:Button("Button", function()
  print("You clicked me")
end)
```
# make dropdown
```lua
local dropdown = folder:DropDown("DropDown", {"Apples", "Bananas", "Oranges", "Kiwis", "Pears"}, function(value)
  print(value)
end)
```
# make slider
```lua
local slider = folder:Slider("Slider", 0, 500, function(value) 0 is the min and 500 is the max you can change those values
  print(value)
end)
```
# make label
```lua
local label = folder:Label("Hello World!")
```
# update label
```lua
label:Update("New world!")
```
# minimize ui (with force)
```lua
window.Minimize()
```
# is the ui minimized?
```lua
print(window.IsMinimized()) -- true/false
```
# why is it obfuscated
cuz my code bad
