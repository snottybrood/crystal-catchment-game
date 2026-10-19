# Crystal Catchment

A strategy simulation game where players manage water, cities, and ecosystems across evolving landscapes while balancing survival, growth, droughts, floods, and long-term sustainability.

---

## Overview

Crystal Catchment is an environmental civilization simulator focused on the interconnected relationship between human development and the water cycle.

Players are tasked with developing a vulnerable region surrounded by critical water resources and flood-prone terrain. Using a limited infrastructure deck, players must balance expansion, water demand, ecological resilience, and disaster mitigation in order to keep their civilization alive.

The game blends:
- City-building simulation
- Environmental systems modeling
- Resource management
- Hazard and disaster gameplay
- Climate resilience strategy

Crystal Catchment explores how infrastructure, population growth, conservation, and land use affect long-term water sustainability.

---

## Gameplay

Players are taken to Crystal Catchment, a newly planned development in a geographically sensistive area. Players have a limited infrastructure deck which must be managed to keep the residents of Crystal Catchment alive. Choose from resilience factors like reservoirs, and stress factors like farms and dense populations in order to build a civilization that is capable of surviving long-term environmental pressures while maintaining a balanced water budget. The factors and resources are not static. Wells run dry, farms fail, drought can collaspe a population, and its up to you to create a sustainable program that will last.


Each decision impacts:
- Water availability
- Flood risk
- Groundwater recharge
- Population stability
- Ecological health
- Economic sustainability

---

## Win Condition

Maintain population stability and prevent catastrophic drought collapse.

---

## Current Release

Version 1 represents the foundational prototype of Crystal Catchment.

This release introduces the core gameplay loop and establishes the framework for future environmental simulation systems, resilience mechanics, and climate adaptation gameplay.

Crystal Catchment is designed as both:
- an experimental strategy game
- a civic-tech engagement tool focused on water resilience and hazard mitigation

The long-term vision is to evolve the project into a deeper climate adaptation and environmental planning simulator.

October 2026
Crystal Catchment v1.1: Bug-Fix Release

Gameplay bugs

Starting settlement fixed. The starting farm and forest were often silently skipped when the start tile bordered water, which left new games without food. Every game now starts with a well, house, farm and forest.
Game pauses behind dialogs. The simulation used to keep running while the intro, help or game-over screen was open, draining food before you could act. It now waits until you close the dialog.
Reservoirs now store water. They used to release more than they collected, so storage stayed near zero. Reservoirs now capture runoff from their own tile and higher ground around them, store up to 200 units, and release it slowly.
Events follow game time. Event cooldowns used real-world time, so they kept counting down while the game was paused and didn’t match the speed setting. They now count game ticks.
Event effects can’t repeat. Drought, flood, hurricane and water-war effects could be applied again while their warning was on cooldown. Effects now fire only when the event does.

Science accuracy

Forests help rain soak in. Reforested tiles were treated like paved buildings and absorbed less rain than bare ground. They now have full forest infiltration.
Groundwater flows between tiles. Water now moves slowly from wetter to drier ground, so a well draws down the aquifer around it (a “cone of depression”) instead of draining its own tile in a few ticks.

Interface fixes

Help and intro text now show their paragraph breaks.
Log entries show the correct tick instead of always [T000].
Starting a new game resets the speed, pause and build-mode controls.
The build preview now uses the same rules as actual placement, including desalination on coastal land only, and hovering over an invalid tile explains why.
The hover highlight updates as you move the mouse instead of once per tick.
Tooltips stay on screen near the edges and can no longer break on descriptions containing quotes.
Gauges only turn red or amber where low values are bad (humidity, groundwater). Cold temperatures and dry ground no longer look like alarms.
The rainfall gauge is rescaled so normal rain is visible.
The trend chart’s water line now shows supply as a percentage of demand.
The game timer stops on game over.

New

Keyboard shortcuts: Space pauses, Esc cancels build mode, Enter closes dialogs.
Starting population is 40 instead of 50, for a fairer opening.

---

## Planned Features (V2 Wishlist)

### World & Progression
- 5 progressively difficult levels/maps
- Free-play sandbox mode
- Region-specific hydrology and rainfall systems
- 100-year resilience campaign mode

### Environmental Systems
- Flood events and floodplain mechanics
- Snowpack variability and seasonal meltwater
- Dynamic desertification and ecological recovery
- Expanded climate variability systems

### Infrastructure & Economy
- Economic scaling and inflation systems
- Resource scarcity progression
- New infrastructure types:
  - Cities
  - Data centers
  - Advanced water systems

### Population & Society
- Dynamic population growth
- Water conservation behavior ("water affinity")
- Stability-driven migration and expansion

### Gameplay Systems
- Achievement and awards system
- Long-term sustainability scoring
- Expanded disaster mitigation mechanics

---

## Vision

Crystal Catchment is built around a simple question:

How long can a civilization survive when water becomes the defining constraint?

The project aims to make environmental systems visible, interactive, and understandable through emergent strategy gameplay.

---

## Attribution

When sharing or redistributing this project, please attribute:

**Black Lattice Consulting © 2026**
