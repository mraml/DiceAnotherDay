# Dungeon Delver: A Roguelike Solitaire Card Game

## Game Overview
Dungeon Delver is a roguelike solitaire card game played with a standard 52-card deck and a d20 die. You'll navigate through a dangerous dungeon, battle monsters, collect treasure, and try to defeat the final boss before your health reaches zero.

## Setup

1. Remove the four Jacks from the deck and place them face up.
2. Choose one Jack as your character class:
   - Jack of Hearts: Healer
   - Jack of Diamonds: Rogue
   - Jack of Clubs: Warrior
   - Jack of Spades: Mage
3. Set your starting health to 20 (track with a separate counter or paper).
4. Shuffle the remaining 48 cards thoroughly and place them face down as the dungeon deck.

## Character Classes

### Healer (Jack of Hearts)
- **Special Ability**: Once per floor, restore 1d6 health.
- **Starting Item**: Healing Potion (restore 2 health when used)

### Rogue (Jack of Diamonds)
- **Special Ability**: Can peek at one trap card per floor before deciding to disarm.
- **Starting Item**: Lockpick (automatically disarm one trap)

### Warrior (Jack of Clubs)
- **Special Ability**: +2 to all attack rolls against monsters.
- **Starting Item**: Shield (prevent 2 damage once per floor)

### Mage (Jack of Spades)
- **Special Ability**: Once per floor, can reroll any die roll.
- **Starting Item**: Magic Scroll (skip one monster encounter)

## Gameplay

The game is played through a series of dungeon floors. Each floor contains 12 cards from the dungeon deck.

### Dungeon Floor Layout
1. Deal 12 cards face down in a 3×4 grid. This represents one floor of the dungeon.
2. You must clear the entire floor before proceeding to the next floor.
3. You can tackle cards in any order you choose.

### Card Types
When you flip a card, its suit and value determine what you encounter:

#### Hearts (2-10): Health Items
- Value = Amount of health restored
- You can save these for later use

#### Diamonds (2-10): Treasure
- Value = Gold pieces found
- Collect treasure to upgrade equipment between floors

#### Clubs (2-10): Monsters
- Value = Monster's strength
- Roll d20 to attack:
  - Roll > Monster's value: Defeat monster, take card as trophy
  - Roll ≤ Monster's value: Take damage equal to (monster value - roll)

#### Spades (2-10): Traps
- Value = Trap difficulty
- Roll d20 to disarm:
  - Roll > Trap's value: Successfully disarm, no effect
  - Roll ≤ Trap's value: Take damage equal to trap value

#### Face Cards: Special Encounters
- **Queens**: Mini-bosses (strength 12)
  - Must be defeated before fighting the King boss
  - Roll d20 to attack:
    - Roll > 12: Defeat Queen, gain 5 health
    - Roll ≤ 12: Take damage equal to (12 - roll)
- **Kings**: Floor Bosses (strength 15)
  - Must defeat to proceed to next floor
  - Roll d20 to attack:
    - Roll > 15: Defeat King, gain 10 gold and 3 health
    - Roll ≤ 15: Take damage equal to (15 - roll)

#### Aces: Special Items
- **Ace of Hearts**: Full health restoration
- **Ace of Diamonds**: Treasure chest (gain 15 gold)
- **Ace of Clubs**: Magic weapon (+2 to all attack rolls for current floor)
- **Ace of Spades**: Teleport (skip to the King boss of current floor)

## Between Floors
After clearing a floor (defeating all 12 cards including the King), you can spend gold on upgrades:
- 10 gold: Increase max health by 2
- 8 gold: Healing potion (restore 5 health)
- 12 gold: Magic shield (prevent damage from one encounter)
- 15 gold: Magic weapon (+1 to all attack rolls permanently)

## Final Boss
After clearing 4 floors, you face the final boss:
1. The boss has 30 health
2. You attack first, rolling d20 and dealing damage equal to your roll
3. Boss attacks, rolling d20 and dealing damage equal to half the roll (rounded down)
4. Continue alternating until either you or the boss is defeated

## Victory Conditions
- Defeat the final boss
- Record your remaining health and gold as your final score

## Defeat Conditions
- Your health reaches 0
- Record the floor you reached and remaining gold as your score

## Optional Rules

### Hardcore Mode
- No health restoration between floors
- Monster damage is doubled

### Speedrun
- Timer set for 20 minutes
- Score is (remaining health + gold + remaining time in minutes)

### Cursed Dungeon
- After clearing each floor, add the four Jacks back to the deck and reshuffle
- When you encounter a Jack, roll d20:
  - 1-10: Curse (lose 3 max health)
  - 11-20: Blessing (gain 2 max health)

This game combines strategic decision-making with the luck of card draws and dice rolls, creating a different experience each time you play. The different character classes provide various playstyles to master.
