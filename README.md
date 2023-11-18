# Gaming Experience Improvement Project

This document outlines a list of user experience and technical compatibility guidelines to help people get the most out of a game.

These guidelines are intended to save players time, prevent frustration, ensure the most people can enjoy a game, and present the best first impression.

## Benefits for players

- Enjoy trying more games which follow these guidelines
- Configure graphics for your computer and monitor
- Configure controls for your needs and preferences
- Avoid common game frustrations

## Benefits for developers

- A checklist for development.
- Ways to help your game give a good first impression, feel high quality and polished.
- Ways to help players enjoy your game over a longer period of time.
- Implement common feature requests 

# The Guidelines

## Controls

#### MENU_INTERACTION

Main and in-game menus should react to mouse clicks and key presses, not just one or the other.

#### HOLD_TO_ACTIVATE

"Hold key to activate/use/switch/open" control schemes can feel heavy and tedious on PC. Developers should consider whether an action like opening a door really needs to ensure a more deliberate key press. Many players will appreciate being able to disable "hold to activate" controls globally or setting "hold for alternate action" to separate keys. Holding should also be avoided in menus, except perhaps in the case of a particularly destructive action, like deleting an entire profile or valuable in-game item.

#### ALLOW_CONTROL_REMAPPING

Players will appreciate being able to switch to controls that they are most comfortable or familiar with. Remapping may also increase the accessibility of your game for some players.

#### NORMAL_MOUSE_SPEED

The mouse sensitivity of a game should be based on the current system settings or at least typical settings for games. The default sensitivity and acceleration curves, especially for menus, maps, and similar interfaces outside of camera or object movement should feel conventional and not drastically slower or faster than similar games or the desktop.

#### CHANGE_CONTROLS_WHILE_PLAYING

The control options should be accessible from the menu during gameplay, not just at the main menu, both to make quick adjustments and for player reference.

## Graphics

### Resolution

#### DEFAULT_RESOLUTION

The default resolution for a game on a fresh install should very likely be the same resolution as the rest of the operating system, or at the very least the same aspect ratio.

- Stretched resolutions with a different aspect ratio might make it hard to navigate the graphics menu to the right resolution.
- If the default resolution is lower than the monitor, a player's first impression will be a pixelated or blurry version of the game.
- If the default resolution is higher than the monitor, parts of the menu may not be visible, or difficult to read.

#### ULTRAWIDE_SUPPORT

Games should support ultra-wide resolutions and allow HUD elements to be brought towards the center for easier viewing. 

### Performance

#### SHOW_FPS

A game should allow the framerate to be displayed in the game. This will help players to be able tune the graphics to their liking, and allow players to report areas of the game that have framerate drops.

#### FRAMERATE_LIMIT

A game should allow the framerate to limited to a customizable amount. There is usually not an advantage to exceeding the monitors framerate, and in other situations like a performance intensive game or using laptop computer it can be beneficial to set a lower maximum framerate to improve framerate consistency or reduce heat and fan noise.

#### GRAPHICS_BENCHMARK

An included automatic graphics benchmark can be very valuable when a player is determining the best balance of graphics and performance for their computer. Ideally this should be accessible directly from the graphics options to test new configurations. A very clever game developer could use a few trials of the benchmark to suggest appropriate graphics settings for a given computer. As a benefit fot developers, games that offer automated benchmarks may be more likely to be included in hardware reviews, increasing exposure.

### Effects

#### MOTION_BLUR

Motion blur effects should be disable-able. Motion blur is a divisive feature, with some fans and some foes, and many players will appreciate the option to disable it. Given that human eyes already do not perceive fash motion perfectly, and many displays still have a noticeable response time, blurring of fast motion will still take place to an extent.

#### DEPTH_OF_FIELD

Depth of field effects should be disable-able. Some players are bothered by any blur, like MOTION_BLUR, but also depth of field. Those players will appreciate the option to disable it. Since the eye has its sharpest perception in the center anyway, there is often still a perceptual blur effect of farther parts of the image taking place.

#### HEAD_BOBBING

Head bobbing should be disable-able. Head bobbing may increase immersion and fun for some players, but for others it may lead to annoyance or even motion sickness. Though our heads do not glide along perfectly smoothly in real life, our bodies and brains compensate for this to the extent that we often don't perceive it.

### Graphics Options

#### SUPPORT_WINDOWED

Windowed and windowed-fullscreen modes should be supported for a game to allow players who may need or want to multitask with video overlays or chats.

#### CONFIRM_RESOLUTION

It's good to confirm after changing a resolution since some resolutions may not show up in a useable way on all monitors.

#### CHANGE_GRAPHICS_FROM_GAME

Graphic options should be changeable from the in-game menu and not just the main menu, since needed changes may not be apparent until the player is actually in-game observing the performance. Games should avoid or automate requiring restarts for settings changes as much their architectures permit.


## Videos, tutorials, and dialogues

#### SKIP_INTRO

Introduction logos and videos should be skippable, disable-able, or even only show for the first launch. Players are excited to get to the game, not see the studio logo or wait for an animation they've already seen dozens or hundreds of times.

#### SKIP_CUTSCENE

Cutscenes should be skippable with a key press. A player may have already seen the cutscene because they are reloading a save file or replaying the whole game. The player may also just be the type of person that cares much more for gameplay than story.

### ADVANCE_DIALOGUE

Dialogue should be advance-able with a click or key press. Depending on whether a player has already heard or read this dialogue in a previous attempt or play-through, if they are reading the subtitles faster than the voices are speaking, or are just more interested in the gameplay then the story, they will appreciate being able to speed through dialogue. 

### SKIP_TUTORIAL

Games should allow player to skip the tutorial, as well as try it again from the main menu. They may be replaying the game.

## Saved Games

#### NAMED_PROFILES

Games should allow for organizing save games in named profiles. The game should should provide information to help players determine which save file they want, like:
  1. The profile name
  2. The real time and date last played
  3. The progress through the game or character level, if applicable
  4. The character type or class, if applicable

- If a player wants to replay a game or resumes a game after a long break, they may wish to create a new profile / campaign / character / save slot so that they have context, or to re-enjoy the game content in order.
- If a player wants to share the game with another person using the same computer, separate saved games are very helpful for that.
- Relying on users to move or manage one set of saved files is not a good experience: Steam cloud syncing may overwrite files in unpredictable ways, and it doesn't allow for multiple players without managing files each time the player switches.

#### LOTS_OF_SAVE_SLOTS

A game should not limit the number of profiles arbitrarily to some small number of separate play-throughs, like 2 or 4. It is unlikely that the saved game files take up enough space to limit them like this, and the players with the most saves are likely to be some of the biggest fans of a game.

## Desktop interaction

#### ALT_TAB

Games should allow players to switch to other applications on their computer without the game crashing or failing to restore. A player might be looking up a hint for the game, inviting someone else via chat, or just checking on anything else on their computer during a long session.

#### BACKGROUND_FRAMERATE

If a game is minimized, it should reduce its resource consumption, either by pausing with a menu or limiting the framerate rendered as appropriate for different types of games. Bonus points for allowing the user to set the background framerate.

#### AUTO_RESTART

If a game's graphics or update architecture unavoidably requires restarts, why not restart the game for the user? Bonus points for opening a full screen spinner or progress bar as another process for a smooth experience.
