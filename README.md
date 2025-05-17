# Super Smash Mobs (Open Source Edition)

An open-source re-creation of Mineplex's iconic minigame Super Smash Mobs!

This is not guaranteed to be a perfect carbon copy of the original game. Rather, the goal is for this project to be a "faithful *enough*" version with appropriate changes and improvements.

This code was originally forked from [Whoneedspacee/SSMOS](https://github.com/Whoneedspacee/SSMOS).

## Download

Downloads may be found in the GitHub releases.

## Installation

> [!NOTE]
This guide assumes that you are familiar with the basics of running a Minecraft server. If you're not, check out this wiki article. This repo includes a sample Docker Compose file if it helps.

TODO: compose file

1. Download [PandaSpigot](https://github.com/hpfxd/PandaSpigot) to use as your server JAR. Make sure your server

2. Place `super-smash-mobs-1.0.jar` inside your `plugins/` directory.

3. TODO: map instructions

## Compiling

*The guide below uses IntelliJ IDEA Community Edition 2025.1.1.*

1. Clone this repository and open it with your IDE. Let any initialization finish before proceeding.

2. TODO: add build configurations for IntelliJ?

### Iterative testing

1. Press the "maven" menu, expand the "lifecycle" tab and click the "install" button

2. Wait for the IDE to successfully compile your code, which should end in a "BUILD SUCCESS"

3. If you want to quickly and easily test your changes, you can run the start.bat within the "ssmos-template-server", since the .jar automatically builds to the plugins folder

4. Alternatively, under the "projects" menu, expand the "target" directory, and copy-paste the file titled "SSMOS-1.0.jar" into your desired plugins folder

note: The template server does not come with maps pre-installed, you will have to gather these yourself.

## Contributing

Pull requests and contributions are both welcomed and encouraged! If you have a large set of changes, please try to split it up into different branches/PR's so that it's easier to review.
