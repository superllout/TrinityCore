# Copyright (C) 2008-2014 TrinityCore <http://www.trinitycore.org/>
#
# This file is free software; as a special exception the author gives
# unlimited permission to copy and/or distribute it, with or without
# modifications, as long as this notice is preserved.
#
# This program is distributed in the hope that it will be useful, but
# WITHOUT ANY WARRANTY, to the extent permitted by law; without even the
# implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

set(scripts_STAT_SRCS
  ${scripts_STAT_SRCS}
    Custom/npc_mmr_reset.cpp
    Custom/npc_shop.cpp
    Custom/Duel_Reset.cpp
    Custom/channel_factions.cpp
    Custom/hunterpet_vendor.cpp
    Custom/mod_MultiKill.cpp
    Custom/npc_arena_team_top.cpp
    Custom/top5_killers.cpp
    
)

message("  -> Prepared: Custom")
