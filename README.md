local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Da Hood :)", "GrapeTheme")


local Tab = Window:NewTab("Main")
local Section = Tab:NewSection("Main")
Section:NewButton("Fly X", "Very OP Enjoin:)", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/v3wQE/flying/main/README.md"))();
end)

Section:NewButton("ShazamFly", "Very OP Enjoin:)", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/22kristina/swag/main/admin_fly"))()
end)

local Tab = Window:NewTab("GodMode")
local Section = Tab:NewSection("GodMode")
Section:NewToggle("FullGodMode", "Very OP Enjoin:)", function(state)
    if state then
        loadstring(game:HttpGet("https://pastebin.com/raw/6Ts8rvyB"))();print("Toggle On")
    else
        loadstring(game:HttpGet("https://pastebin.com/raw/6Ts8rvyB"))();print("Toggle Off")
    end
end)

local Tab = Window:NewTab("Toggle")
local Section = Tab:NewSection("Toggle")

Section:NewToggle("Reach", "Very OP Enjoin:)", function(state)
    if state then
        loadstring(game:HttpGet("https://pastebin.com/raw/pBem7cwn"))();print("Toggle On")
    else
        loadstring(game:HttpGet("https://pastebin.com/raw/pBem7cwn"))();print("Toggle Off")
    end
end)

Section:NewToggle("AntiStomp", "Very OP Enjoin:)", function(state)
    if state then
        loadstring(game:HttpGet("https://pastebin.com/raw/is5rxXPD"))();print("Toggle On")
    else
        loadstring(game:HttpGet("https://pastebin.com/raw/is5rxXPD"))();print("Toggle Off")
    end
end)

Section:NewToggle("AntiFling", "Very OP Enjoin:)", function(state)
    if state then
        loadstring(game:HttpGet("https://pastebin.com/raw/bSTV82KY"))();print("Toggle On")
    else
        loadstring(game:HttpGet("https://pastebin.com/raw/bSTV82KY"))();print("Toggle Off")
    end
end)
