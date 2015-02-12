#On Load

Title screen should render, which it currently does. Audio will play, and a "start" button will be present

#click start

on clicking the "start" button, the background elements should remain, as this will be the backdrop for the character selection screen, and for the actual sparring area.

character selection 'windows should appear as three proportional, vertically oriented rectangles.

when a character is selected, a "fight" button will appear beneath the character box.

#click fight

on clicking the "fight" button, the character selection boxes should vanish, a message of some kind, indicated the game start should display, and the player's selected character should appear on the left hand side of the screen. The area at the bottom (action menu) should now have attack and heal buttons present. The same divs used in the start screen for the hero and the enemy will be used during the game.

#game

player's chosen hero should fight against a randomly selected enemy (right now they're all Llamas). clicking an "attack" button should deal damage against the enemy if the conditions are met (math.random). the enemy will then have a turn of their own, with the same rules and abilities.

#endgame

if the player's health reaches zero before the enemy, a "defeat" message will be displayed, along with a "replay" button. If the enemy's health reaches zero before the player's, a "victory" message will be displayed, along with a "replay" button. The "replay" button will reset/reload the application state.
