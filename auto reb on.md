_G.Autofarm = true
while _G.Autofarm == true do
wait(1)
para = game:GetService("Players")["Alones_Darkness"].PlayerGui.GUI.Money.Value
if para > 1.2277255824917285e+47 then
wait()
print("Rebirthed EzW")
local Event = game:GetService("ReplicatedStorage").Rebirth
Event:InvokeServer()
wait(2.5)
local A_1 = "Load"
local A_2 = "Layout2"
local Event = game:GetService("ReplicatedStorage").Layouts
Event:InvokeServer(A_1, A_2)
wait(7)
end
end
