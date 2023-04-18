# peacock ui library
## Getting Loadstring
```lua
local Library = loadstring(game:HttpGet('https://raw.githubusercontent.com/iliekmen/i-liek-men-project/main/peacock%20but%20better%20(removed%20hide%20gui%20and%20notifcation)', true))()
```
## Creating Window
```lua
local Window = Library:CreateLib {
	name = "Name"
}
```

## Creating Tabs
```lua
local Tab = Window:NewTab({
	name = "Name",
	icon = "rbxassetid://3926305904"
})
```

## Creating Buttons
```lua

local Button = Tab:NewButton({
	name = "Name"
})
Button:SetCallback(function()
	
end)
```

## Creating Labels
```lua
local Label = Tab:NewLabel({
	name = "Name"
})
```

## Creating Sliders
```lua
local Slider = Tab:NewSlider({
	name = "Name",
	min = "16", -- (min 16) to (max 100) min is the lowest max is the highest and default choose to 16 to 100
	max = "100",
	default = "16"
})
Slider:SetCallback(function(v)
	game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = v -- if you want JumpPower Change the WalkSpeed To JumpPower
end)
```

## Creating Toggles
```lua
local Toggle = Tab:NewToggle({
	name = "Name"
  ----probably paste script right here (peacock devoloper didnt tell anything)
})
Toggle:SetCallback(function(v)
	print(v)
end)
```

