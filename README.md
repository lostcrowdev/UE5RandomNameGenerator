# Random Name Generator - Unreal Engine 5

A lightweight, data-driven random name generator component for Unreal Engine 5.7.  
Generate realistic or completely new names for NPCs or any actor at runtime.

The system supports first, middle, and last names, gender filtering.

---

## Features

- Random First, Middle, and Last Name generation
- Toggle First / Middle / Last names on or off
- Gender filtering for first and middle names
  - Female
  - Male
  - Unisex
- Fully data-driven
- Uses Data Tables so you can easily import custom name lists
- Component-based
  - Simply attach the component to any actor
- Runtime name generation for NPCs or gameplay systems

## Setup

### 1. Add the Component

Add the Random Name Generator Component to any actor.

Example:
- NPC Character
- AI Pawn

---

### 2. Assign Data Tables

Create or import CSV name lists and convert them to Data Tables using the S_Names struct for rows. Look at the example Data Tables for reference.

## Planned development:

- Replication support for multiplayer
- Save generated names to save files
- Automatically add actor tags based on generated names
- Procedural name generator that creates new names by combining parts of existing ones