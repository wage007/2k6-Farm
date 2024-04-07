# 2k6-Farm

This is an auto farmer for da hood, it is opened source. If you decide to skid, leave credits.



# How to setup

1. Dont be dumb, use an alt
2. Config is self explanitory, webhook goes in the ["Webhook"]
3. Don't change credits
4. Keep fps below 60, you will crash


# Features 

1. Changeable methods of auto-farming - (fast punching, super punch, knife)
2. Webhook logging.
3. Log Intervals (webhooks)
4. Code redeeming


# LOADER BELOW
-
_G.AutofarmSettings = {
    ["AttackMode"] = "3", -- 1 - Fast Punch | 2 - Super Punch | 3 - Knife (PROB THE FASTEST).

    ["Fps"] = "60", -- dont go above 60

    ["Codes"] = { -- dont be retarded and change
        "DAUP", 
        "HALLOWEEN2023",
        "MELONBEAR",
        "THANKSGIVING23",
        "KART",
        "pumpkins2023",
        "CANDYCANE2023",
        "REINDEER2023",
        "SNOWMAN2023" ,
        "HOODMAS2023" ,
        "XMAS2023"
 }, 

    ["Webhook"] = "https://discord.com/api/webhooks/1226244506249330748/xo0yjH9_uDycmxfI_POn3CfwLJPzLLIwRGPCxsDmOC9apsXoRpC2k8wrVUiNW9d3KEVg", -- put ur webhook here
    ["LogInterval"] = "2", -- dont change
    ["Credits"] = "2k6 Farm - by @threat5" -- dont change
}

loadstring(game:HttpGet("https://raw.githubusercontent.com/wage007/2k6-Farm/main/source.luau"))()

