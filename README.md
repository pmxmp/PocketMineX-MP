<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/readme/pocketminex-dark.png">
    <source media="(prefers-color-scheme: light)" srcset=".github/readme/pocketminex-light.png">
    <img alt="PocketMineX-MP" src=".github/readme/pocketminex-light.png">
  </picture>
</p>

<p align="center"><b>A highly customisable, open source server software for Minecraft: Bedrock Edition written in PHP</b></p>

<p align="center">
  <a href="https://github.com/pmxmp/PocketMineX-MP/actions"><img alt="CI" src="https://img.shields.io/github/actions/workflow/status/pmxmp/PocketMineX-MP/main.yml?label=CI"></a>
  <a href="https://github.com/pmxmp/PocketMineX-MP/releases/latest"><img alt="release" src="https://img.shields.io/github/v/release/pmxmp/PocketMineX-MP?label=release"></a>
  <a href="https://github.com/pmxmp/PocketMineX-MP/releases"><img alt="downloads" src="https://img.shields.io/github/downloads/pmxmp/PocketMineX-MP/total?label=downloads"></a>
</p>

## What is this?

**PocketMineX-MP** is a fork of [axolotl-pm/PocketMine-MP](https://github.com/axolotl-pm/PocketMine-MP), which is itself derived from the original [PocketMine-MP](https://github.com/pmmp/PocketMine-MP) — a highly customisable server software for Minecraft: Bedrock Edition, built from scratch in PHP, with over 10 years of history behind it.

This fork exists to provide ongoing maintenance and, where possible, improvements on top of the upstream axolotl-pm codebase.

If you're looking to create a Minecraft: Bedrock server with **custom functionality**, look no further.

- 🧩 **Powerful plugin API** - extend and customise gameplay as you see fit
- 🗺️ **Rich ecosystem** and **large developer community** - find plugins easily and learn to develop your own
- 🌐 **Multi-world support** - offer a more varied game experience to players without transferring them to other server nodes
- 🏎️ **Performance** - get 100+ players onto one server (depending on hardware and plugins)
- ⤴️ **Continuously updated** - new Minecraft versions are usually supported quickly

## ❌ PocketMineX-MP is NOT a vanilla Minecraft server software.

**It is poorly suited to hosting vanilla survival servers.** It doesn't have many features from the vanilla game, such as vanilla world generation, redstone, mob AI, and various other things.

If you just want to play **vanilla survival multiplayer**, consider using the [official Minecraft: Bedrock server software](https://minecraft.net/download/server/bedrock) instead.

If that's not an option for you, you may be able to add some of the missing features using plugins from [Poggit](https://poggit.pmmp.io/plugins), or write plugins to implement them yourself.

## Getting Started

- [Building from source](BUILDING.md)
- [Upstream documentation (axolotl-pm/PocketMine-MP)](http://pmmp.readthedocs.org/)
- [Plugin repository](https://poggit.pmmp.io/plugins)

## Status

This project is actively maintained. Expect regular updates to track upstream protocol and dependency changes, alongside our own fixes and enhancements.

## Developing Plugins

If you want to write your own plugins, the following upstream resources may be useful:

- [Developer documentation](https://devdoc.pmmp.io) - General documentation for PocketMine-MP plugin developers
- [DevTools](https://github.com/pmmp/DevTools/) - Development tools plugin for creating plugins
- [ExamplePlugin](https://github.com/pmmp/ExamplePlugin/) - Example plugin demonstrating some basic API features

## Contributing

Issues and pull requests are welcome. Please make sure any changes are tested against a live client connection before submitting.

- [Building and running from source](BUILDING.md)
- [Contributing Guidelines](CONTRIBUTING.md)

## Licensing information

This project is licensed under LGPL-3.0. Please see the [LICENSE](LICENSE) file for details.

PocketMineX-MP is not affiliated with Mojang. All brands and trademarks belong to their respective owners. It is not a Mojang-approved software, nor is it associated with Mojang.
