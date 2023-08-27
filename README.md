local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local TextLabel_Frame = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local NameHub_TextLabel = Instance.new("TextLabel")
local Button_Frame = Instance.new("Frame")
local UICorner_3 = Instance.new("UICorner")
local Button_Frame_TextButton = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local Frame_2 = Instance.new("Frame")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(81, 81, 81)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.289799094, 0, 0.13429752, 0)
Frame.Size = UDim2.new(0, 435, 0, 425)

UICorner.Parent = Frame

TextLabel_Frame.Name = "TextLabel_Frame"
TextLabel_Frame.Parent = Frame
TextLabel_Frame.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
TextLabel_Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_Frame.BorderSizePixel = 0
TextLabel_Frame.Size = UDim2.new(0, 435, 0, 40)

UICorner_2.Parent = TextLabel_Frame

NameHub_TextLabel.Name = "Name-Hub_TextLabel"
NameHub_TextLabel.Parent = TextLabel_Frame
NameHub_TextLabel.BackgroundColor3 = Color3.fromRGB(95, 95, 95)
NameHub_TextLabel.BackgroundTransparency = 1.000
NameHub_TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
NameHub_TextLabel.BorderSizePixel = 0
NameHub_TextLabel.Position = UDim2.new(0.0206896551, 0, 0.075000003, 0)
NameHub_TextLabel.Size = UDim2.new(0, 426, 0, 33)
NameHub_TextLabel.Font = Enum.Font.SourceSansBold
NameHub_TextLabel.Text = "Name-Hub"
NameHub_TextLabel.TextColor3 = Color3.fromRGB(38, 38, 38)
NameHub_TextLabel.TextSize = 33.000
NameHub_TextLabel.TextXAlignment = Enum.TextXAlignment.Left

Button_Frame.Name = "Button_Frame"
Button_Frame.Parent = ScreenGui
Button_Frame.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
Button_Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Button_Frame.BorderSizePixel = 0
Button_Frame.Position = UDim2.new(0.289799094, 0, 0.191115707, 0)
Button_Frame.Size = UDim2.new(0, 132, 0, 392)

UICorner_3.Parent = Button_Frame

Button_Frame_TextButton.Name = "Button_Frame_TextButton"
Button_Frame_TextButton.Parent = Button_Frame
Button_Frame_TextButton.BackgroundColor3 = Color3.fromRGB(95, 95, 95)
Button_Frame_TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
Button_Frame_TextButton.BorderSizePixel = 0
Button_Frame_TextButton.Position = UDim2.new(0.0606060624, 0, 0.0586734712, 0)
Button_Frame_TextButton.Size = UDim2.new(0, 116, 0, 26)
Button_Frame_TextButton.Font = Enum.Font.SourceSansBold
Button_Frame_TextButton.Text = "Name-Button"
Button_Frame_TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
Button_Frame_TextButton.TextSize = 25.000

UICorner_4.Parent = Button_Frame_TextButton

Frame_2.Parent = Button_Frame_TextButton
Frame_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(1.12931037, 0, -0.307692319, 0)
Frame_2.Size = UDim2.new(0, 289, 0, 371)
