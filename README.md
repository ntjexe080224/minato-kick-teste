-- minato kick 
-- Version: 3.2
 
-- Instances:
 
local RudraAdminGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Kick = Instance.new("Folder")
local TextButton = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local PlayerName = Instance.new("TextBox")
local Reason = Instance.new("TextBox")
local Ban = Instance.new("Folder")
local TextLabel_2 = Instance.new("TextLabel")
local PlayerName_2 = Instance.new("TextBox")
local TextButton_2 = Instance.new("TextButton")
local Reason_2 = Instance.new("TextBox")
local Title = Instance.new("TextLabel")
 
--Properties:
 
RudraAdminGui.Name = "RudraAdminGui"
RudraAdminGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
RudraAdminGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
RudraAdminGui.ResetOnSpawn = false
 
Frame.Parent = RudraAdminGui
Frame.BackgroundColor3 = Color3.fromRGB(170, 255, 255)
Frame.Position = UDim2.new(0.19628647, 0, 0.252485096, 0)
Frame.Size = UDim2.new(0, 550, 0, 309)
 
Kick.Name = "Kick"
Kick.Parent = Frame
 
TextButton.Parent = Kick
TextButton.BackgroundColor3 = Color3.fromRGB(85, 170, 0)
TextButton.BackgroundTransparency = 0.250
TextButton.Position = UDim2.new(0.890804589, 0, 0.158576056, 0)
TextButton.Size = UDim2.new(0, 50, 0, 50)
TextButton.Font = Enum.Font.LuckiestGuy
TextButton.LineHeight = 0.750
TextButton.Text = "Kick"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true
 
TextLabel.Parent = Kick
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0.0249042138, 0, 0.15910238, 0)
TextLabel.Size = UDim2.new(0, 210, 0, 50)
TextLabel.Font = Enum.Font.SciFi
TextLabel.Text = "Kick A Player"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true
 
PlayerName.Name = "PlayerName"
PlayerName.Parent = Kick
PlayerName.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PlayerName.BackgroundTransparency = 1.000
PlayerName.Position = UDim2.new(0.427203059, 0, 0.161812291, 0)
PlayerName.Size = UDim2.new(0, 249, 0, 49)
PlayerName.ClearTextOnFocus = false
PlayerName.Font = Enum.Font.SciFi
PlayerName.PlaceholderColor3 = Color3.fromRGB(76, 76, 76)
PlayerName.PlaceholderText = "Enter player name here"
PlayerName.Text = ""
PlayerName.TextColor3 = Color3.fromRGB(0, 0, 0)
PlayerName.TextScaled = true
PlayerName.TextSize = 14.000
PlayerName.TextWrapped = true
 
Reason.Name = "Reason"
Reason.Parent = Kick
Reason.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Reason.BackgroundTransparency = 1.000
Reason.Position = UDim2.new(0.0249042306, 0, 0.320388347, 0)
Reason.Size = UDim2.new(0, 525, 0, 50)
Reason.ClearTextOnFocus = false
Reason.Font = Enum.Font.SciFi
Reason.PlaceholderColor3 = Color3.fromRGB(76, 76, 76)
Reason.PlaceholderText = "Enter reason here"
Reason.Text = ""
Reason.TextColor3 = Color3.fromRGB(0, 0, 0)
Reason.TextScaled = true
Reason.TextSize = 14.000
Reason.TextWrapped = true
Reason.TextXAlignment = Enum.TextXAlignment.Left
 
Ban.Name = "Ban"
Ban.Parent = Frame
 
TextLabel_2.Parent = Ban
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(0.0236363634, 0, 0.537216842, 0)
TextLabel_2.Size = UDim2.new(0, 226, 0, 41)
TextLabel_2.Font = Enum.Font.SciFi
TextLabel_2.Text = "Ban A Player"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true
TextLabel_2.TextXAlignment = Enum.TextXAlignment.Left
 
PlayerName_2.Name = "PlayerName"
PlayerName_2.Parent = Ban
PlayerName_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PlayerName_2.BackgroundTransparency = 1.000
PlayerName_2.Position = UDim2.new(0.427203029, 0, 0.546925545, 0)
PlayerName_2.Size = UDim2.new(0, 249, 0, 44)
PlayerName_2.ClearTextOnFocus = false
PlayerName_2.Font = Enum.Font.SciFi
PlayerName_2.PlaceholderColor3 = Color3.fromRGB(76, 76, 76)
PlayerName_2.PlaceholderText = "Enter player name here"
PlayerName_2.Text = ""
PlayerName_2.TextColor3 = Color3.fromRGB(0, 0, 0)
PlayerName_2.TextScaled = true
PlayerName_2.TextSize = 14.000
PlayerName_2.TextWrapped = true
 
TextButton_2.Parent = Ban
TextButton_2.BackgroundColor3 = Color3.fromRGB(85, 170, 0)
TextButton_2.BackgroundTransparency = 0.250
TextButton_2.Position = UDim2.new(0.890804529, 0, 0.546925545, 0)
TextButton_2.Size = UDim2.new(0, 50, 0, 50)
TextButton_2.Font = Enum.Font.LuckiestGuy
TextButton_2.LineHeight = 0.750
TextButton_2.Text = "Ban"
TextButton_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.TextScaled = true
TextButton_2.TextSize = 14.000
TextButton_2.TextWrapped = true
 
Reason_2.Name = "Reason"
Reason_2.Parent = Ban
Reason_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Reason_2.BackgroundTransparency = 1.000
Reason_2.Position = UDim2.new(0.0249042306, 0, 0.679611623, 0)
Reason_2.Size = UDim2.new(0, 525, 0, 55)
Reason_2.ClearTextOnFocus = false
Reason_2.Font = Enum.Font.SciFi
Reason_2.PlaceholderColor3 = Color3.fromRGB(76, 76, 76)
Reason_2.PlaceholderText = "Enter reason here"
Reason_2.Text = ""
Reason_2.TextColor3 = Color3.fromRGB(0, 0, 0)
Reason_2.TextScaled = true
Reason_2.TextSize = 14.000
Reason_2.TextWrapped = true
Reason_2.TextXAlignment = Enum.TextXAlignment.Left
 
Title.Name = "Title"
Title.Parent = Frame
Title.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title.BackgroundTransparency = 1.000
Title.Size = UDim2.new(0, 386, 0, 50)
Title.Font = Enum.Font.SciFi
Title.Text = "Rudra's Admin GUI"
Title.TextColor3 = Color3.fromRGB(0, 0, 0)
Title.TextScaled = true
Title.TextSize = 14.000
Title.TextWrapped = true
