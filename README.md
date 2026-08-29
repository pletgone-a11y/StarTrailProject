# Star Trail Launcher

> A lightweight, open-source Minecraft launcher focused on simplicity, customization and performance.

Star Trail Launcher is an open-source Minecraft launcher designed to provide a simple and customizable way to manage Minecraft installations, instances and modpacks.
## Screenshots

<p align="center">
  <img src="docs/screenshots/launcher.png" width="45%">
  <img src="docs/screenshots/instances.png" width="45%">
</p>


## Features

* Lightweight and easy to use
* Minecraft instance management
* Modpack support
* Customizable launcher interface
* Borderless window support
* Open-source and community-driven
* No unnecessary background processes
* Multiple Offline account support
* Modrinth and Curseforge for modpacks and mods search sistem
* Export/Import in .mrpack your instance
* Screeenshot gallery
* Full customizable settings
* Automatic download and setup java runtimes for instances
* Played time for modpack (requires ST on background)

## Status

**Star Trail Launcher is currently in development.**

Features may change, break, or be incomplete while the project is being developed.

## Installation

### Windows

Download the latest installer from the [Releases](../../releases) page and follow the installation instructions.

> The installer is the recommended way to install Star Trail Launcher.

<details>
<summary>Building from source</summary>

### Requirements

* [Node.js](https://nodejs.org/)
* [Rust](https://www.rust-lang.org/)
* Tauri prerequisites for your operating system

### Setup

Clone the repository:

```bash
git clone https://github.com/pletgone-a11y/star-trail-launcher.git
cd STL
```

Install dependencies:

```bash
npm install
```

Run the launcher in development mode:

```bash
npm run tauri dev
```

Build a production release:

```bash
npm run tauri build
```

The generated application bundles can be found in:

```text
src-tauri/target/release/bundle/
```

</details>

## Contributing

Contributions, bug reports, and suggestions are welcome.

If you find a bug or have an idea for Star Trail Launcher, feel free to open an issue.

Pull requests are also welcome.

## License

Star Trail Launcher is licensed under the **GNU General Public License v3.0**.

See the [LICENSE](LICENSE) file for the full license text.

## Disclaimer

Star Trail Launcher is an independent open-source project and is not affiliated with, endorsed by, or sponsored by Mojang Studios or Microsoft.
