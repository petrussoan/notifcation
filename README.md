-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(84, 84, 84)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.859987378, 0, 0.855787516, 0)
Frame.Size = UDim2.new(0, 183, 0, 31)

UICorner.CornerRadius = UDim.new(0, 44)
UICorner.Parent = Frame

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.0601092875, 0, -0.0967741907, 0)
TextLabel.Size = UDim2.new(0, 160, 0, 36)
TextLabel.Font = Enum.Font.SourceSansBold
TextLabel.Text = "C To fly And V keybind close and open!"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 11.000
TextLabel.TextWrapped = true
