--create By FRITE--
while true do wait()
local args = {
    [1] = {
        ["multiply"] = 4,
        ["action"] = "hit",
        ["enemyHum"] = workspace.dummies.TrainingDummy4.Humanoid
    }
}

game:GetService("ReplicatedStorage").DamageEvent:FireServer(unpack(args))
end
