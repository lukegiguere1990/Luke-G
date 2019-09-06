# Luke G's eso problem pls help!

lua script error in eso using master merchant and awesome guild store pls help!

user:/AddOns/AwesomeGuildStore/backend/SearchManager.lua:373: attempt to index a nil value
stack traceback:
user:/AddOns/AwesomeGuildStore/backend/SearchManager.lua:373: in function 'SearchManager:HasCurrentSearchMorePages'
|caaaaaa<Locals> self = tbl, guildId = 345753 </Locals>|r
user:/AddOns/AwesomeGuildStore/backend/SearchManager.lua:380: in function 'SearchManager:RequestSearch'
|caaaaaa<Locals> self = tbl, guildId = 345753 </Locals>|r
user:/AddOns/AwesomeGuildStore/backend/SearchManager.lua:47: in function 'DoSearch'
EsoUI/Ingame/TradingHouse/Gamepad/TradingHouse_Gamepad.lua:131: in function 'ZO_GamepadTradingHouse:EnterBrowseResults'
|caaaaaa<Locals> self = tbl </Locals>|r
EsoUI/Ingame/TradingHouse/Gamepad/TradingHouse_Browse_Gamepad.lua:92: in function 'callback'
EsoUI/Libraries/ZO_KeybindStrip/ZO_KeybindStrip.lua:645: in function 'ZO_KeybindStrip:TryHandlingKeybindDown'
|caaaaaa<Locals> self = tbl, keybind = "UI_SHORTCUT_SECONDARY", buttonOrEtherealDescriptor = ud, keybindButtonDescriptor = tbl </Locals>|r
(tail call): ?
(tail call): ?

anyone have a fix?
