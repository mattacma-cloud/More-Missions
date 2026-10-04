# More Missions 
<img width="750" height="300" alt="MoreMissions jpg" src="https://github.com/user-attachments/assets/d1ba9692-0fdf-438f-a1d5-512573479c16" />

More Missions adds thirteen new mission types to BattleTech, giving players new challenges to face in their games. 
These missions were built using CWolf’s Mission Control editor and owe a lot to the work of the new missions team at BTA: 
KOS, BD, taintedloki, Wulf, Bluewinds, and to Kierk who got those missions ready for BEXT.

***These missions are currently in early release***

Only a single mission, each set up as a Flashpoint is available. 

For those using these missions for testing, please let me know what works, what doesn’t and what could be done better in each 
mission. Once testing is complete, a larger set of missions for each type will be created across different biomes/maps and 
released for use.

If you would like to contribute to the testing / improvement of these missions, please reach out to me on Discord 
(User ID: Stareater1) and I’ll add you to the development chat, or you can reach out to me here.

## **Activating the Mission Shapes for Testing**

The method for playtesting the mission shapes is set up as a series of interlinked, 1 mission flashpoints that stay open 
for 10 years. This gives players time to recover and plan for each in turn. The first flashpoint will appear at 
Novaya Zemlya in the Capellan March of the Federated Suns as soon as it can spawn via an event that asks if you want to take 
the mission.

The missions and their locations are all one world apart and follow the path below:

No.  Mission - World

+ 1	  Combat Patrol - Novaya Zemlya
+ 2	  Major Push - Kluane
+ 3	  Rapid Advance - Fortymile
+ 4	  Planetary Landing - Sekulmun
+ 5	  Planetary Evacuation - Kigamboni
+ 6	  Complex Assignment - Cumberland
+ 7	  Contested Ground - Mordialloc
+ 8	  Reconnaissance - Kaitangata
+ 9	  Scout Hunt - Okains
+ 10	Prevent the Landing - Oltepesi
+ 11	Prevent the Evacuation - Firgrove
+ 12	The Vice - New Syrtis
+ 13	By the Sword - Hobson

Each of the missions will appear on the contract screen list of contracts in green, for easy identification.

Alternatively, you can use the BattleTech Save Editor to give your company all of the following tags. 
You will then spawn all 13 mission offers in a row and can accept them all, activating all 13 Flashpoints, 
which you can then do in any order you like.

Mission			              Completion Tag

+ Combat Patrol		          (event_phase2_combatpatrol_done)
+ Major Push		            (event_phase2_majorpush_done)
+ Rapid Advance		          (event_phase2_rapidadvance_done)
+ Planetary Landing	        (event_phase2_planetarylanding_done)
+ Planetary Evacuation	    (event_phase2_planetaryevacuation_done)
+ Complex Assignment	      (event_phase2_complexassignment_done)
+ Contested Ground	        (event_phase2_contestedground_done)
+ Reconnaissance		        (event_phase2_reconnaissance_done)
+ Scout Hunt		            (event_phase2_scouthunt_done)
+ Prevent the Landing	      (event_phase2_preventthelanding_done)
+ Prevent the Evacuation	  (event_phase2_preventtheevacuation_done)
+ The Vice		              (event_phase2_thevice_done)
+ By the Sword		          (event_phase2_bythesword_done)

## Installation

**Step 1**

Drag and drop the folders into your mods folder.

**Step 2**

Ensure you have also downloaded the LorePack_Helpersmod from here (https://github.com/mattacma-cloud/Lore-Packs/tree/main)

Go into the mod.json and change     

`"ContractIdContains": [ "c_fp_lp", "touring_tikonov" ],`

to

`"ContractIdContains": [ "c_fp_lp", "touring_tikonov", "TheVice_CapitolHillTest" ],`

**Step 3**

Go to BTX_CAC_Compatibility and in the mod.json, in the `"Use4LimitOnContractIds":` list change the last line from

`      "c_fp_tMTM_3B_ThreeWayBattle"t"`

to

`      "c_fp_tMTM_3B_ThreeWayBattle",\
      "ByTheSword_CragMireTest"
`
