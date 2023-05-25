# The Development Process

## Areas of Interest

AOIs are the heart of the new zone that we're developing. Think of the zone as a county, and the AOIs are the cities within that county. Each AOI is developed primarily by an Environment Artist and a World Designer, and is put together as a self-contained, unique location for players to experience.

Each AOI is broken down into a level of complexity that helps define their size, scope, and expected amount of time to develop. This helps prevent scope creep, as the complexity can always be considered when adding features to an AOI.

Regardless of complexity, the AOI development pipeline is broken down in the following order

1. Reference Gathering. This is not done per AOI, but rather all at once to help ensure a holistic vision

2. Concept Art

3. Layout. This is a relatively quick process of getting the AOI blocked out in 3D. A lot of art used is placeholder color blocks, but it gives the artists and designers a visual space to work in and plan out the player experience

4. Asset Placement. This is when blocks start getting replaced with 3D assets. Even these assets are still often placeholder, but are representative of the size and shape of what to expect from final assets, just without the final level of fidelity

5. Enemy Placement. With the Layout complete, Designers can start placing enemy AI within the AOI, plotting out patrol paths and behaviors.

6. Set Dressing. Similar to asset placement, but with a lot of the finer artistic details that go into an AOI, like books on a shelf or dishes on a table.

7. VFX. Once assets and enemies are in place, the VFX artist can go in and start adding bespoke visual effects to the AOI

8. Final Pass. This is the longest part of the process. Once all of the elements of the AOI have been developed individually, the Final Pass is done that manipulates and fine tunes all of them at once to make sure everything comes together

## Environment Biome

The biome is an integral part to the player experience, and actually very time consuming. It drives the overall look and feel of the entire zone, all of the terrain and vegetation elements, which requires a lot of variety to keep players from getting visually bored.

Biome asset complexity is tied directly to their size, because larger pieces of vegetation require more variety and detail in their materials. Trees are the most time intensive, as they require varieties with different branches, leaf canopies, bark, etc. This is followed by bushes, and finally ground cover.

Like other 3D Environment assets, proxy models are created first so that visual representations of size and shape are available for use while the more labor intensive final artistic details get worked on.

## Weapons

The expansion pack is going to include a new weapon type for each of our existing character classes, for seven new weapons in total. Each weapon goes through the following stages of development

1. Reference Gathering. Unlike AOIs, reference needs to be gathered on a per-weapon basis

2. Concept Art

3. Modeling. This is the meat of weapon development. It starts with a hi-poly sculpt at high detail, which is then reduced to low-poly for performance needs.

4. VFX. Once the weapon model is complete, VFX artists add their touches to the weapon, such as glowing runes or muzzle flashes

## Systems

While the pipeline for a new gameplay system is incredibly simple, the actual work involved is anything but. Gameplay systems go through a process of documentation followed by implementation, but both of those are an extensive process. Implementation in particular requires significant play testing and tweaking of small elements to ensure appropriate game balance across the board.

## New Enemy

Designing a new enemy for the game can be a complicated task! This includes the following pipeline

1. Reference gathering

2. Concept Art

3. Paper Design. Before any 3D work is done on a creature, it needs a compelling design on paper that outlines the different abilities that it has, the type of fight experience players should have, and other important factors.

4. Modeling. Once the idea for the enemy is down on paper, artists can begin to make the 3D model of the creature, keeping those design elements in mind

5. Rigging. After the 3D model is created, an animation rig needs to be built for the creature. The rig acts as a skeleton under the creature, and provides all of the components necessary to properly animate it

6. Attack and Idle Animations. Once a rig is created, animators can start creating the animations necessary. Creatures always needs idle animations, things like fidgeting or walking, or other things they might do when not engaged in combat with players.

7. Design Scripting. Once animations are done, Design comes back in and sets all of the behaviors. This is where they start executing on the paper design they made at the start, determining what the AI for the creature is capable of.

8. Effects. Finally, once the scripting is done, VFX and SFX come in and add the final flourishes.



## Quests

The quest narrative is an integral part of the expansion The main story quest line is what drives players through the content, and needs to tell a story while also breadcrumbing players to each of the new locations and make sure they gradually experience all of the new content.

The main story quest is difficult to detail upfront, because so much of it depends on play testing and tweaking based on the player experience. As such, in the project planning, the main story quests are intentionally not quantified. Instead, there is a set amount of time allocated for developing those quests, and the Quest Designer works within that time box to create the best experience - whether that is 10 big quests or 100 small ones.

The other part of the quest design comes with repeatable quests, which are a lot easier to quantify. These are meant to bring players back every day, and are typically simple tasks so as not to annoy players while still giving them a steady flow of rewards that they can use.

Regardless of type, there are three main components to the quest design workflow

1. Quest Design. This is the paper element of the design, and is usually fairly straightforward, like a narrative storyboard. "In this quest, I want the player to run around the city rescuing civilians from bad guys." Though straightforward, it sets the ground work for the rest of the process and so usually takes the longest

2. Dialog writing. Every quest needs to be given by a character and then that same character needs to be told when it's done, and these book ends require dialog that sets the stage.

3. Design scripting. While fairly easy, this can also be tedious, and represents the under-the-hood part of quest design. This phase of the process ensures players are appropriately getting credit for quest steps they complete, are given accurate navigational elements on their map, etc.
