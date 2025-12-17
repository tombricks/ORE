ORE (which stands for nothing) is a HOI4 mod which strips the game as close to the metal as it can without removing the tags and states (for now, this will presumably change).

REMAINING ENTRIES

common/autonomous_states/00_autonomous_states.txt is blank but this causes a crash when trying to release a puppet

common/bookmarks/00_bookmarks.txt has a blank bookmark with only a "---" entry so the game can be entered

common/buildings/00_buildings.txt is stripped as far as it can be

common/continuous_focus/00_continuous_focus.txt has an empty focus palette or it crashes before mainmenu

common/national_focus/00_national_focus.txt has a blank focus tree to avoid crash but no focuses or styles are defined

common/resources/00_resources.txt has a load_bearing_resource which is referenced in 00_defines.lua

common/special_projects/specialization/00_specialiations.txt has the default specializations or it crashes

common/units/equipment/00_equipment.txt has load_bearing_equipment train to avoid crash

KNOWN CRASHES

releasing a puppet

entering a peace conference

going to build equipment