"+" Added in Zero Hour  
"-" Removed from Zero Hour

<details><summary>DamageType</summary>

```
EXPLOSION
CRUSH
ARMOR_PIERCING
SMALL_ARMS
GATTLING
RADIATION
FLAME
LASER
SNIPER
POISON
HEALING
UNRESISTABLE
WATER
DEPLOY
SURRENDER
HACK
KILL_PILOT
PENALTY
FALLING
MELEE
DISARM
HAZARD_CLEANUP
PARTICLE_BEAM
TOPPLING
INFANTRY_MISSILE
AURORA_BOMB
LAND_MINE
JET_MISSILES
STEALTHJET_MISSILES
MOLOTOV_COCKTAIL
COMANCHE_VULCAN
//FLESHY_SNIPER -
SUBDUAL_MISSILE +
SUBDUAL_VEHICLE +
SUBDUAL_BUILDING +
SUBDUAL_UNRESISTABLE +
MICROWAVE +
KILL_GARRISONED +
STATUS +
```
</details>


<details><summary>KindOfType</summary>

```
OBSTACLE
SELECTABLE
IMMOBILE
CAN_ATTACK
STICK_TO_TERRAIN_SLOPE
CAN_CAST_REFLECTIONS
SHRUBBERY
STRUCTURE
INFANTRY
VEHICLE
AIRCRAFT
HUGE_VEHICLE
DOZER
HARVESTER
COMMANDCENTER
LINEBUILD
SALVAGER
WEAPON_SALVAGER
TRANSPORT
BRIDGE
LANDMARK_BRIDGE
BRIDGE_TOWER
PROJECTILE
PRELOAD
NO_GARRISON
WAVEGUIDE
WAVE_EFFECT
NO_COLLIDE
REPAIR_PAD
HEAL_PAD
STEALTH_GARRISON
CASH_GENERATOR
//AIRFIELD -
DRAWABLE_ONLY
MP_COUNT_FOR_VICTORY
REBUILD_HOLE
SCORE
SCORE_CREATE
SCORE_DESTROY
NO_HEAL_ICON
CAN_RAPPEL
PARACHUTABLE
CAN_BE_REPULSED
MOB_NEXUS
IGNORED_IN_GUI
CRATE
CAPTURABLE
CLEARED_BY_BUILD
SMALL_MISSILE
ALWAYS_VISIBLE
UNATTACKABLE
MINE
CLEANUP_HAZARD
PORTABLE_STRUCTURE
ALWAYS_SELECTABLE
ATTACK_NEEDS_LINE_OF_SIGHT
WALK_ON_TOP_OF_WALL
DEFENSIVE_WALL
FS_POWER
FS_FACTORY
FS_BASE_DEFENSE
FS_TECHNOLOGY
AIRCRAFT_PATH_AROUND
LOW_OVERLAPPABLE
FORCEATTACKABLE
AUTO_RALLYPOINT
TECH_BUILDING
POWERED
PRODUCED_AT_HELIPAD
DRONE
CAN_SEE_THROUGH_STRUCTURE
BALLISTIC_MISSILE
CLICK_THROUGH
SUPPLY_SOURCE_ON_PREVIEW
PARACHUTE
GARRISONABLE_UNTIL_DESTROYED
BOAT
IMMUNE_TO_CAPTURE
HULK
SHOW_PORTRAIT_WHEN_CONTROLLED
SPAWNS_ARE_THE_WEAPONS
CANNOT_BUILD_NEAR_SUPPLIES
SUPPLY_SOURCE
REVEAL_TO_ALL
DISGUISER
INERT
HERO
IGNORES_SELECT_ALL
DONT_AUTO_CRUSH_INFANTRY
CLIFF_JUMPER +
FS_SUPPLY_DROPZONE +
FS_SUPERWEAPON +
FS_BLACK_MARKET +
FS_SUPPLY_CENTER +
FS_STRATEGY_CENTER +
MONEY_HACKER +
ARMOR_SALVAGER +
REVEALS_ENEMY_PATHS +
BOOBY_TRAP +
FS_FAKE +
FS_INTERNET_CENTER +
BLAST_CRATER +
PROP +
OPTIMIZED_TREE +
FS_ADVANCED_TECH +
FS_BARRACKS +
FS_WARFACTORY +
FS_AIRFIELD +
AIRCRAFT_CARRIER +
NO_SELECT +
REJECT_UNMANNED +
CANNOT_RETALIATE +
TECH_BASE_DEFENSE +
EMP_HARDENED +
DEMOTRAP +
CONSERVATIVE_BUILDING +
IGNORE_DOCKING_BONES +
```
</details>

<details><summary>ObjectStatusType</summary>

```
NONE
DESTROYED
CAN_ATTACK
UNDER_CONSTRUCTION
UNSELECTABLE
NO_COLLISIONS
NO_ATTACK
AIRBORNE_TARGET
PARACHUTING
REPULSOR
HIJACKED
AFLAME
BURNED
WET
IS_FIRING_WEAPON
IS_BRAKING
STEALTHED
DETECTED
CAN_STEALTH
SOLD
UNDERGOING_REPAIR
RECONSTRUCTING
MASKED
IS_ATTACKING
USING_ABILITY
IS_AIMING_WEAPON
NO_ATTACK_FROM_AI
IGNORING_STEALTH
IS_CARBOMB
DECK_HEIGHT_OFFSET +
STATUS_RIDER1 +
STATUS_RIDER2 +
STATUS_RIDER3 +
STATUS_RIDER4 +
STATUS_RIDER5 +
STATUS_RIDER6 +
STATUS_RIDER7 +
STATUS_RIDER8 +
FAERIE_FIRE +
KILLING_SELF +
REASSIGN_PARKING +
BOOBY_TRAPPED +
IMMOBILE +
DISGUISED +
DEPLOYED +
```
</details>

<details><summary>DeathType</summary>

```
NORMAL
NONE
CRUSHED
BURNED
EXPLODED
POISONED
TOPPLED
FLOODED
SUICIDED
LASERED
DETONATED
SPLATTED
POISONED_BETA
EXTRA_2
EXTRA_3
EXTRA_4
EXTRA_5
EXTRA_6
EXTRA_7
EXTRA_8
POISONED_GAMMA +
```
</details>


<details><summary>BehaviorModules</summary>

```
AutoHealBehavior
GrantStealthBehavior +
NeutronBlastBehavior +
BridgeBehavior
BridgeScaffoldBehavior
BridgeTowerBehavior
CountermeasuresBehavior +
DumbProjectileBehavior
PhysicsBehavior
InstantDeathBehavior
SlowDeathBehavior
HelicopterSlowDeathBehavior
NeutronMissileSlowDeathBehavior
CaveContain
OpenContain
OverchargeBehavior
HealContain
GarrisonContain
InternetHackContain +
TransportContain
RiderChangeContain +
RailedTransportContain
MobNexusContain
TunnelContain
OverlordContain
HelixContain +
ParachuteContain
PropagandaTowerBehavior
BunkerBusterBehavior +
FireWeaponWhenDamagedBehavior
FireWeaponWhenDeadBehavior
GenerateMinefieldBehavior
ParkingPlaceBehavior
FlightDeckBehavior +
PoisonedBehavior
RebuildHoleBehavior
SupplyWarehouseCripplingBehavior
TechBuildingBehavior
MinefieldBehavior
BattleBusSlowDeathBehavior +
JetSlowDeathBehavior
RailroadBehavior
SpawnBehavior
DestroyDie
FXListDie
CrushDie
DamDie
CreateCrateDie
CreateObjectDie
EjectPilotDie
SpecialPowerCompletionDie
RebuildHoleExposeDie
UpgradeDie
KeepObjectDie
AssistedTargetingUpdate
AutoFindHealingUpdate
BaseRegenerateUpdate
StealthDetectorUpdate
StealthUpdate
//DelayedWeaponSetUpgradeUpdate -
DeletionUpdate
SmartBombTargetHomingUpdate +
DynamicShroudClearingRangeUpdate
DeployStyleAIUpdate
AssaultTransportAIUpdate
HordeUpdate
ToppleUpdate
EnemyNearUpdate
LifetimeUpdate
RadiusDecalUpdate
EMPUpdate
LeafletDropBehavior +
AutoDepositUpdate
WeaponBonusUpdate +
MissileAIUpdate
NeutronMissileUpdate
FireSpreadUpdate
FireWeaponUpdate
FlammableUpdate
FloatUpdate
TensileFormationUpdate
HeightDieUpdate
ChinookAIUpdate
JetAIUpdate
AIUpdateInterface
SupplyTruckAIUpdate
DeliverPayloadAIUpdate
HackInternetAIUpdate
DynamicGeometryInfoUpdate
FirestormDynamicGeometryInfoUpdate
LaserUpdate
PointDefenseLaserUpdate
CleanupHazardUpdate
CommandButtonHuntUpdate
PilotFindVehicleUpdate
DemoTrapUpdate
ParticleUplinkCannonUpdate
SpectreGunshipUpdate +
SpectreGunshipDeploymentUpdate +
BaikonurLaunchPower
BattlePlanUpdate
ProjectileStreamUpdate
QueueProductionExitUpdate
RepairDockUpdate
RailedTransportDockUpdate
DefaultProductionExitUpdate
SpawnPointProductionExitUpdate
SpyVisionUpdate
SlavedUpdate
MobMemberSlavedUpdate
OCLUpdate
SpecialAbilityUpdate
MissileLauncherBuildingUpdate
SupplyCenterProductionExitUpdate
SupplyCenterDockUpdate
SupplyWarehouseDockUpdate
DozerAIUpdate
RailedTransportAIUpdate
ProductionUpdate
ProneUpdate
StickyBombUpdate
FireOCLAfterWeaponCooldownUpdate
HijackerUpdate
StructureToppleUpdate
StructureCollapseUpdate
BoneFXUpdate
RadarUpdate
AnimationSteeringUpdate +
TransportAIUpdate
WanderAIUpdate
WaveGuideUpdate
WorkerAIUpdate
PowerPlantUpdate
CheckpointUpdate
CostModifierUpgrade
ActiveShroudUpgrade
ArmorUpgrade
CommandSetUpgrade
//DelayedUpgrade -
GrantScienceUpgrade +
PassengersFireUpgrade +
StatusBitsUpgrade
SubObjectsUpgrade
StealthUpgrade
RadarUpgrade
PowerPlantUpgrade
LocomotorSetUpgrade
ObjectCreationUpgrade
ReplaceObjectUpgrade +
ModelConditionUpgrade +
UnpauseSpecialPowerUpgrade
WeaponBonusUpgrade
WeaponSetUpgrade
WeaponBonusUpgrade
ExperienceScalarUpgrade
MaxHealthUpgrade
LockWeaponCreate +
PreorderCreate
SupplyCenterCreate
SupplyWarehouseCreate
SpecialPowerCreate
GrantUpgradeCreate
VeterancyGainCreate
BoneFXDamage
TransitionDamageFX
FireWeaponCollide
SquishCollide
HealCrateCollide
MoneyCrateCollide
ShroudCrateCollide
UnitCrateCollide
VeterancyCrateCollide
ConvertToCarBombCrateCollide
ConvertToHijackedVehicleCrateCollide
SabotageCommandCenterCrateCollide +
SabotageFakeBuildingCrateCollide +
SabotageInternetCenterCrateCollide +
SabotageMilitaryFactoryCrateCollide +
SabotagePowerPlantCrateCollide +
SabotageSuperweaponCrateCollide +
SabotageSupplyCenterCrateCollide +
SabotageSupplyDropzoneCrateCollide +
SalvageCrateCollide
InactiveBody
ActiveBody
HighlanderBody
ImmortalBody
StructureBody
HiveStructureBody
UndeadBody +
CashHackSpecialPower
DefectorSpecialPower
OCLSpecialPower
FireWeaponPower +
SpecialAbility
SpyVisionSpecialPower
CashBountyPower
CleanupAreaPower
AnimatedParticleSysBoneClientUpdate
SwayClientUpdate
BeaconClientUpdate
```
</details>

<details><summary>SpecialPowerType</summary>

```
SPECIAL_INVALID
SPECIAL_DAISY_CUTTER
SPECIAL_PARADROP_AMERICA
SPECIAL_CARPET_BOMB
SPECIAL_CLUSTER_MINES
SPECIAL_EMP_PULSE
SPECIAL_NAPALM_STRIKE
SPECIAL_CASH_HACK
SPECIAL_NEUTRON_MISSILE
SPECIAL_SPY_SATELLITE
SPECIAL_DEFECTOR
SPECIAL_TERROR_CELL
SPECIAL_AMBUSH
SPECIAL_BLACK_MARKET_NUKE
SPECIAL_ANTHRAX_BOMB
SPECIAL_SCUD_STORM
SPECIAL_DEMORALIZE_OBSOLETE
SPECIAL_CRATE_DROP
SPECIAL_A10_THUNDERBOLT_STRIKE
SPECIAL_DETONATE_DIRTY_NUKE
SPECIAL_ARTILLERY_BARRAGE
SPECIAL_MISSILE_DEFENDER_LASER_GUIDED_M...
SPECIAL_REMOTE_CHARGES
SPECIAL_TIMED_CHARGES
SPECIAL_HELIX_NAPALM_BOMB
SPECIAL_HACKER_DISABLE_BUILDING
SPECIAL_TANKHUNTER_TNT_ATTACK
SPECIAL_BLACKLOTUS_CAPTURE_BUILDING
SPECIAL_BLACKLOTUS_DISABLE_VEHICLE_HACK
SPECIAL_BLACKLOTUS_STEAL_CASH_HACK
SPECIAL_INFANTRY_CAPTURE_BUILDING
SPECIAL_RADAR_VAN_SCAN
SPECIAL_SPY_DRONE
SPECIAL_DISGUISE_AS_VEHICLE
SPECIAL_BOOBY_TRAP
SPECIAL_REPAIR_VEHICLES
SPECIAL_PARTICLE_UPLINK_CANNON
SPECIAL_CASH_BOUNTY
SPECIAL_CHANGE_BATTLE_PLANS
SPECIAL_CIA_INTELLIGENCE
SPECIAL_CLEANUP_AREA
SPECIAL_LAUNCH_BAIKONUR_ROCKET
SPECIAL_SPECTRE_GUNSHIP
SPECIAL_GPS_SCRAMBLER
SPECIAL_FRENZY
SPECIAL_SNEAK_ATTACK
SPECIAL_CHINA_CARPET_BOMB
EARLY_SPECIAL_CHINA_CARPET_BOMB
SPECIAL_LEAFLET_DROP
EARLY_SPECIAL_LEAFLET_DROP
EARLY_SPECIAL_FRENZY
SPECIAL_COMMUNICATIONS_DOWNLOAD
EARLY_SPECIAL_REPAIR_VEHICLES
SPECIAL_TANK_PARADROP
SUPW_SPECIAL_PARTICLE_UPLINK_CANNON
AIRF_SPECIAL_DAISY_CUTTER
NUKE_SPECIAL_CLUSTER_MINES
NUKE_SPECIAL_NEUTRON_MISSILE
AIRF_SPECIAL_A10_THUNDERBOLT_STRIKE
AIRF_SPECIAL_SPECTRE_GUNSHIP
INFA_SPECIAL_PARADROP_AMERICA
SLTH_SPECIAL_GPS_SCRAMBLER
AIRF_SPECIAL_CARPET_BOMB
SUPR_SPECIAL_CRUISE_MISSILE
LAZR_SPECIAL_PARTICLE_UPLINK_CANNON
SUPW_SPECIAL_NEUTRON_MISSILE
SPECIAL_BATTLESHIP_BOMBARDMENT
```
</details>

<!---
<details><summary<Template</summary>

```

```
</details>
-->
