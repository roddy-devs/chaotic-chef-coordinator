# Overcooked 2 Role Assignment Bot Instructions

## Project Goal
Create a Discord bot that aids groups playing Overcooked 2 by rapidly assigning roles to players, enhancing their gaming experience through efficient, real-time coordination.

## Core Features
- **Slash Commands:** Implement commands (/overcooked start, /overcooked roles, /overcooked assign, and /overcooked summary) for initiating and managing game sessions.
- **Dynamic Role Assignment:** According to the number of players, offer a selection of roles each with defined tasks, responsibilities, and priorities.
- **Concurrent Session Support:** Allow multiple game sessions across different servers simultaneously.
- **Session State Management:** Maintain the state per channel to support flow from session start to role assignment.
- **User-Friendly Outputs:** Format the summary of roles and tasks in an emoji-supported, neatly spaced output that is easy to understand mid-game.

## Technical Constraints
- **Language/Framework:** Use Python and the discord.py library exclusively.
- **Intents Configuration:** Properly configure Discord intents for handling messages and interactions.
- **Environment Variables:** Store sensitive data like the bot token in environment variables.
- **File Structure:** Utilize a straightforward structure with main.py, a cogs/ directory for commands, and a utils/ directory for utility functions.

## Quality Expectations
The bot is expected to perform with a rapid response time, allowing players to transition from questioning roles to understanding everyone's tasks in under thirty seconds. It must be capable of managing multiple sessions across different servers without interference or confusion.

## Implementation Notes
- Focus on creating a seamless user interface using buttons and select menus for a gamified experience.
- Ensure that the bot's tone matches the game's fun and lightly chaotic nature, aiming to be perceived as a teammate.
