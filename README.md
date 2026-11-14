--[[===========================================================
  MUTA HUB · ARQUIVO ÚNICO · celular fraco
  Contadores por mutação (máx. 10.000) · chips de atalho
  PT-BR padrão · EN / ES / 中文 / हिन्दी
  Furtivo + limitador + anti-AFK + antihit + botão mobile
  USO: cole no executor com o inventário aberto, escolha o ovo,
       marque os contadores e toque em INICIAR. PARAR corta.
  Se o automático falhar: APRENDER -> aplique 1 na mão -> APRENDER.
  PERFIL (opcional, rode antes):
       getgenv().MUTA_HUB_PERFIL = "baixo" | "medio" | "alto"
===========================================================]]--

local Players = game:GetService("Players")
local RS = game:GetService("ReplicatedStorage")
local WS = game:GetService("Workspace")
local UIS = game:GetService("UserInputService")
local VU = game:GetService("VirtualUser")
local LP = Players.LocalPlayer
local unpack = table.unpack
local lower, find, gsub = string.lower, string.find, string.gsub# Po0
