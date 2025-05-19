---by gojohdkaisenkt---

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Name = Instance.new("TextLabel")
local Credits = Instance.new("TextLabel")
local TextBox = Instance.new("TextBox")
local EpicSaxGuy = Instance.new("TextButton")
local ForceField = Instance.new("TextButton")
local TextBox2 = Instance.new("TextBox")
local UICorner = Instance.new("UICorner")
local UICorner2 = Instance.new("UICorner")
local UICorner3 = Instance.new("UICorner")
local UICorner4 = Instance.new("UICorner")
local TextBox3 = Instance.new("TextBox")
local EpicSaxGuy2 = Instance.new("TextButton")
local message1  = Instance.new("TextButton")
local message2  = Instance.new("TextButton")
--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
ScreenGui.ResetOnSpawn = false

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.Position = UDim2.new(0.382171214, 0, 0.328530252, 0)
Frame.Size = UDim2.new(0, 378, 0, 250)
Frame.Draggable = true

UICorner.Parent = TextBox2
UICorner2.Parent = EpicSaxGuy
UICorner3.Parent = TextBox
UICorner4.Parent = ForceField

Name.Name = "Name"
Name.Parent = Frame
Name.BackgroundColor3 = Color3.fromRGB(0,0,255)
Name.Size = UDim2.new(0, 378, 0, 25)
Name.Font = Enum.Font.GothamBold
Name.Text = "1x1x1x1 Message"
Name.TextColor3 = Color3.fromRGB(0, 0, 0)
Name.TextScaled = true
Name.TextSize = 14.000
Name.TextWrapped = true

Credits.Name = "Credits"
Credits.Parent = Frame
Credits.BackgroundColor3 = Color3.fromRGB(0,0,255)
Credits.Position = UDim2.new(0, 0, 0.912, 0)
Credits.Size = UDim2.new(0, 378, 0, 22)
Credits.Font = Enum.Font.GothamBold
Credits.Text = "By gojohdkaisenkt |  mode: hint"
Credits.TextColor3 = Color3.fromRGB(0, 0, 0)
Credits.TextScaled = true
Credits.TextSize = 14.000
Credits.TextWrapped = true

TextBox.Parent = Frame
TextBox.BackgroundColor3 = Color3.fromRGB(0,0,255)
TextBox.Position = UDim2.new(0.0714285746, 0, 0.216111119, 0)
TextBox.Size = UDim2.new(0, 325, 0, 117)
TextBox.ClearTextOnFocus = false
TextBox.Font = Enum.Font.GothamBold
TextBox.MultiLine = true
TextBox.PlaceholderText = "write here"
TextBox.Text = ""
TextBox.TextColor3 = Color3.fromRGB(1, 1,1 )
TextBox.TextSize = 17.000
TextBox.TextStrokeTransparency = 0.000
TextBox.TextWrapped = true
TextBox.TextXAlignment = Enum.TextXAlignment.Left
TextBox.TextYAlignment = Enum.TextYAlignment.Top

EpicSaxGuy.Name = "EpicSaxGuy"
EpicSaxGuy.Parent = Frame
EpicSaxGuy.BackgroundColor3 = Color3.fromRGB(0,0,255)
EpicSaxGuy.Position = UDim2.new(0.388888896, 0, 0.748000002, 0)
EpicSaxGuy.Size = UDim2.new(0, 83, 0, 34)
EpicSaxGuy.Font = Enum.Font.GothamBold
EpicSaxGuy.Text = "execute"
EpicSaxGuy.TextColor3 = Color3.fromRGB(0, 0, 0)
EpicSaxGuy.TextScaled = true
EpicSaxGuy.TextSize = 14.000
EpicSaxGuy.TextWrapped = true
EpicSaxGuy.MouseButton1Down:connect(function()

local message = Instance.new("Hint")
message.Parent = game.Workspace
message.Text = ""..TextBox.Text..""

task.wait(""..TextBox2.Text.."")
 
message:Destroy()
   end)
ForceField.Name = "ForceField"
ForceField.Parent = Frame
ForceField.BackgroundColor3 = Color3.fromRGB(0,0,255)
ForceField.Position = UDim2.new(0.693121672, 0, 0.748000002, 0)
ForceField.Size = UDim2.new(0, 89, 0, 34)
ForceField.Font = Enum.Font.GothamBold
ForceField.Text = "Clear"
ForceField.TextColor3 = Color3.fromRGB(0, 0, 0)
ForceField.TextScaled = true
ForceField.TextSize = 14.000
ForceField.TextWrapped = true
ForceField.MouseButton1Down:connect(function()

local ForceFieldGUI = Instance.new("ScreenGui")
	local ForceFieldGUI_2 = Instance.new("TextButton")
	local ForceFieldOFF = Instance.new("TextButton")
	local ForceFieldON = Instance.new("TextButton")

	--Properties:

	ForceFieldGUI.Name = "ForceFieldGUI"
	ForceFieldGUI.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

	ForceFieldGUI_2.Name = "ForceFieldGUI"
	ForceFieldGUI_2.Parent = ForceFieldGUI
	ForceFieldGUI_2.BackgroundColor3 = Color3.fromRGB(0, 255, 255)
	ForceFieldGUI_2.BackgroundTransparency = 0.300
	ForceFieldGUI_2.BorderColor3 = Color3.fromRGB(245, 244, 247)
	ForceFieldGUI_2.BorderSizePixel = 0
	ForceFieldGUI_2.Position = UDim2.new(0, 0, 0, 240)
	ForceFieldGUI_2.Size = UDim2.new(0, 100, 0, 20)
	ForceFieldGUI_2.Text = "thank for use"
	ForceFieldGUI_2.TextColor3 = Color3.fromRGB(17, 17, 17)
	ForceFieldGUI_2.TextTransparency = 0.300

	ForceFieldOFF.Name = "ForceFieldOFF"
	ForceFieldOFF.Parent = ForceFieldGUI
	ForceFieldOFF.BackgroundColor3 = Color3.fromRGB(253, 253, 253)
	ForceFieldOFF.BackgroundTransparency = 0.300
	ForceFieldOFF.BorderColor3 = Color3.fromRGB(245, 244, 247)
	ForceFieldOFF.BorderSizePixel = 0
	ForceFieldOFF.Position = UDim2.new(0, 0, 0, 280)
	ForceFieldOFF.Size = UDim2.new(0, 100, 0, 20)
	ForceFieldOFF.Visible = false
	ForceFieldOFF.Text = "Clear"
	ForceFieldOFF.TextColor3 = Color3.fromRGB(17, 17, 17)

	ForceFieldON.Name = "ForceFieldON"
	ForceFieldON.Parent = ForceFieldGUI
	ForceFieldON.BackgroundColor3 = Color3.fromRGB(253, 253, 253)
	ForceFieldON.BackgroundTransparency = 0.300
	ForceFieldON.BorderColor3 = Color3.fromRGB(245, 244, 247)
	ForceFieldON.BorderSizePixel = 0
	ForceFieldON.Position = UDim2.new(0, 0, 0, 260)
	ForceFieldON.Size = UDim2.new(0, 100, 0, 20)
	ForceFieldON.Visible = false
	ForceFieldON.Text = "Clear"
	ForceFieldON.TextColor3 = Color3.fromRGB(17, 17, 17)

	-- Scripts:

	TextBox.Text = ""
    TextBox.Text = ""
TextBox3.Text = ""
    TextBox3.Text = ""
end)
-- Scripts:

local function QFCS_fake_script() -- Frame.Dragify 
	local script = Instance.new('LocalScript', Frame)

	local UIS = game:GetService("UserInputService")
	function dragify(Frame)
	    dragToggle = nil
	    local dragSpeed = 0
	    dragInput = nil
	    dragStart = nil
	    local dragPos = nil
	    function updateInput(input)
	        local Delta = input.Position - dragStart
	        local Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + Delta.X, startPos.Y.Scale, startPos.Y.Offset + Delta.Y)
	        game:GetService("TweenService"):Create(Frame, TweenInfo.new(0.25), {Position = Position}):Play()
	    end
	    Frame.InputBegan:Connect(function(input)
	        if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) and UIS:GetFocusedTextBox() == nil then
	            dragToggle = true
	            dragStart = input.Position
	            startPos = Frame.Position
	            input.Changed:Connect(function()
	                if input.UserInputState == Enum.UserInputState.End then
	                    dragToggle = false
	                end
	            end)
	        end
	    end)
	    Frame.InputChanged:Connect(function(input)
	        if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
	            dragInput = input
	        end
	    end)
	    game:GetService("UserInputService").InputChanged:Connect(function(input)
	        if input == dragInput and dragToggle then
	            updateInput(input)
	        end
	    end)
	end
	
	dragify(script.Parent)
end
coroutine.wrap(QFCS_fake_script)()

TextBox2.Parent = Frame
TextBox2.BackgroundColor3 = Color3.fromRGB(0,0,255)
TextBox2.Position = UDim2.new(0.0714285746, 0, 0.748000002, 0)
TextBox2.Size = UDim2.new(0, 83, 0, 34)
TextBox2.ClearTextOnFocus = false
TextBox2.Font = Enum.Font.GothamBold
TextBox2.MultiLine = true
TextBox2.PlaceholderText = "time here"
TextBox2.Text = ""
TextBox2.TextColor3 = Color3.fromRGB(0, 0,0)
TextBox2.TextSize = 17.000
TextBox2.TextStrokeTransparency = 0.000
TextBox2.TextWrapped = true
TextBox2.TextXAlignment = Enum.TextXAlignment.Left
TextBox2.TextYAlignment = Enum.TextYAlignment.Top

TextBox3.Parent = Frame
TextBox3.BackgroundColor3 = Color3.fromRGB(0,0,255)
TextBox3.Position = UDim2.new(0.0714285746, 0, 0.216111119, 0)
TextBox3.Size = UDim2.new(0, 325, 0, 117)
TextBox3.ClearTextOnFocus = false
TextBox3.Font = Enum.Font.GothamBold
TextBox3.MultiLine = true
TextBox3.PlaceholderText = "^_^"
TextBox3.Text = "message mode"
TextBox3.TextColor3 = Color3.fromRGB(1, 1,1 )
TextBox3.TextSize = 17.000
TextBox3.TextStrokeTransparency = 0.000
TextBox3.TextWrapped = true
TextBox3.TextXAlignment = Enum.TextXAlignment.Left
TextBox3.TextYAlignment = Enum.TextYAlignment.Top
TextBox3.Visible = false

EpicSaxGuy2.Name = "EpicSaxGuy2"
EpicSaxGuy2.Parent = Frame
EpicSaxGuy2.BackgroundColor3 = Color3.fromRGB(0,0,255)
EpicSaxGuy2.Position = UDim2.new(0.388888896, 0, 0.748000002, 0)
EpicSaxGuy2.Size = UDim2.new(0, 83, 0, 34)
EpicSaxGuy2.Font = Enum.Font.GothamBold
EpicSaxGuy2.Text = "execute"
EpicSaxGuy2.TextColor3 = Color3.fromRGB(0, 0, 0)
EpicSaxGuy2.TextScaled = true
EpicSaxGuy2.TextSize = 14.000
EpicSaxGuy2.TextWrapped = true
EpicSaxGuy2.Visible = false
EpicSaxGuy2.MouseButton1Down:connect(function()

local message = Instance.new("Message")
message.Parent = game.Workspace
message.Text = ""..TextBox3.Text..""

task.wait(""..TextBox2.Text.."")
 
message:Destroy()
   end)
message1.Name = "message1"
message1.Parent = Frame
message1.BackgroundColor3 = Color3.fromRGB(0,0,255)
message1.Position = UDim2.new(1.0306747, 0, 0.244979918, 0)
message1.Size = UDim2.new(0, 54, 0, 50)
message1.Font = Enum.Font.GothamBold
message1.Text = "message mode"
message1.TextColor3 = Color3.fromRGB(0, 0, 0)
message1.TextScaled = true
message1.TextSize = 14.000
message1.TextWrapped = true
message1.MouseButton1Down:connect(function()

TextBox3.Visible = true
TextBox.Visible = false
UICorner3.Parent = TextBox3
UICorner2.Parent = EpicSaxGuy2
EpicSaxGuy2.Visible = true
EpicSaxGuy.Visible = false
Credits.Text = "By gojohdkaisenkt |  mode: message"
  end)
message2.Name = "message2"
message2.Parent = Frame
message2.BackgroundColor3 = Color3.fromRGB(0,0,255)
message2.Position = UDim2.new(1.03067482, 0, 0, 0)
message2.Size = UDim2.new(0, 54, 0, 50)
message2.Font = Enum.Font.GothamBold
message2.Text = "hint mode"
message2.TextColor3 = Color3.fromRGB(0, 0, 0)
message2.TextScaled = true
message2.TextSize = 14.000
message2.TextWrapped = true
message2.MouseButton1Down:connect(function()

TextBox.Visible = true
TextBox3.Visible = false
UICorner3.Parent = TextBox
UICorner2.Parent = EpicSaxGuy
EpicSaxGuy.Visible = true
EpicSaxGuy2.Visible = false
Credits.Text = "By gojohdkaisenkt |  mode: hint"
   end)
