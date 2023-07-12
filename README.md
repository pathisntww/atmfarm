-- atmfarm

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local BottomLeftLabel = Instance.new("TextLabel")

ScreenGui.Name = "GUI"
ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

Frame.Name = "MainFrame"
Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.Position = UDim2.new(0, 0, 0, 0)
Frame.Size = UDim2.new(1, 0, 1, 0)

TextLabel.Name = "MainText"
TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BackgroundTransparency = 1
TextLabel.Position = UDim2.new(0.5, -100, 0.5, -25)
TextLabel.Size = UDim2.new(0, 200, 0, 50)
TextLabel.Font = Enum.Font.Gotham
TextLabel.Text = "paths atm farm. welcome "..game.Players.LocalPlayer.Name
TextLabel.TextColor3 = Color3.fromRGB(0, 255, 0)
TextLabel.TextSize = 20
TextLabel.TextXAlignment = Enum.TextXAlignment.Center
TextLabel.TextYAlignment = Enum.TextYAlignment.Center

BottomLeftLabel.Name = "BottomLeftText"
BottomLeftLabel.Parent = Frame
BottomLeftLabel.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
BottomLeftLabel.BackgroundTransparency = 1
BottomLeftLabel.Position = UDim2.new(0, 10, 1, -30)
BottomLeftLabel.Size = UDim2.new(0, 250, 0, 20)
BottomLeftLabel.Font = Enum.Font.Gotham
BottomLeftLabel.Text = "GUI was made with path and opensource-AI"
BottomLeftLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
BottomLeftLabel.TextSize = 14
BottomLeftLabel.TextXAlignment = Enum.TextXAlignment.Left

loadstring(game:HttpGet("https://raw.githubusercontent.com/applless/RandomScripts/main/DaHoodAutofarm"))()
