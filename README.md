<div align="center">
  <a href="https://github.com/intergrav/Adrenaline">
    <img src="https://raw.githubusercontent.com/intergrav/branding/main/vital/vital-banner.svg" alt="Vital">
  </a>
  <br />
  <br />
  <p align="center">
    Unofficial alternative to the Essential mod with world hosting features, free cosmetics, and much more!
    <br />
    <a href="https://github.com/intergrav/vital/wiki">Explore the wiki</a>
    ·
    <a href="https://github.com/intergrav/vital/issues">Report Bugs</a>
    ·
    <a href="https://github.com/intergrav/vital/issues">Request Features</a>
  </p>
  <a href="https://modrinth.com/modpack/vital"><img src="https://raw.githubusercontent.com/intergrav/branding/main/vital/vital-badge-modrinth.svg" alt="Available on Modrinth"></a>
  <a href="https://discord.gg/wncdz7e8jy"><img src="https://raw.githubusercontent.com/intergrav/branding/main/vital/vital-badge-discord.svg" alt="Chat on Discord"></a>
</div>

Vital is a modpack designed as an **alternative to [Essential](https://modrinth.com/mod/essential)** (and OptiFine). It includes the majority of Essential and OptiFine's features, including but not limited to: world hosting, cosmetics, many resource pack features, shaders, and a major improvement in rendering and logic performance. It also includes some extra features, like input fixes for Linux and MacOS. This modpack is built and kept in sync with my other project, [Additive](https://modrinth.com/modpack/additive), which only includes the performance and OptiFine features. Want your own mods that aren't included in Vital? Don't worry! You can easily add your favorite mods after installation.

# 🎯 Goals

### ⭐ Essential features

Vital contains quite a few mods to replace [Essential](https://modrinth.com/mod/essential)'s features. These are not as consistent as Essential however they are still very simple to use, and some even have upsides over Essential's offering:

- Free world hosting that's secure and private, and does not require the other players to use it. 
  - Simply click "Open to Friends" in the menu to share to your World Host friends, which they can access through the multiplayer menu. You can also type `/worldhost ip` to get an IP to send to people who aren't using the mod.
- Completely free cosmetics from a marketplace full of community creations. Any other Vital, Cosmetica, or Fabulously Optimized user can see these cosmetics.
  - You can access these in the mod menu or settings menu. You could also visit the [Cosmetica website](https://cosmetica.cc).
- A bunch of neat skin management features.
  - Accessible through the main menu.
- Screenshot improvements, such as previews and a screenshot viewer, along with screenshot uploading and copying.
  - When you take a screenshot, it will give you a few options such as a button to upload the screenshot or copy it to your clipboard, or open it. The main menu also contains a screenshot feature.
- Log into different accounts from ingame, or fix authentication issues without relaunching.
  - Simply go into the multiplayer menu and click on the little authentication button in the top left corner.

### 🚀 Improve performance

Vital is based on and kept in sync with the [Additive](https://modrinth.com/modpack/Additive) modpack, which is based on the [Adrenaline](https://modrinth.com/modpack/adrenaline) modpack. Adrenaline's aim is to significantly improve rendering and game logic performance, along with memory and hardware usage, without compromising on the game's looks or features in any way. This is done with various optimization mods that are actively tested for stability and improvement. Some mods are also pre-configured. Adrenaline wouldn't exist without projects like [Sodium](https://modrinth.com/mod/sodium), so I advise you to donate to mod authors and contributors if you can.

### 🔍 OptiFine features

Vital is based on and kept in sync with the [Additive](https://modrinth.com/modpack/Additive) modpack, which utilizes various mods that offers the same features that OptiFine did while also being modular so that you can remove features you don't want or features that are incompatible with other mods. This includes, but is not limited to:

- Major performance boost from [Adrenaline](https://modrinth.com/modpack/adrenaline)
- OptiFine resource pack features
- Built-in shaders support
- Dynamic lighting from held objects
- Better grass and snow
- OptiFine donator capes (and [free capes](https://github.com/skywardmc/additive/wiki/Supporter-cape))
- [All OptiFine features and more information on the Additive wiki](https://github.com/skywardmc/additive/wiki/Give-up-OptiFine)

### 💡 Other features

Vital also includes some extra features unrelated to OptiFine, although I aim to keep this list of mods minimal. Mods are suitable for the "other features" section if they are lightweight and unobtrusive. This includes things like:

- Small input fixes for MacOS and Linux players
- Borderless fullscreen window setting in the video settings
- [All other features and more information on the Additive wiki](https://github.com/skywardmc/additive/wiki/Extra-features)

### ⚙️ Source-available

All mods in Vital are either open-source or source-available, which means you can view the code of mods and see exactly what they are doing. Vital is also available as [packwiz projects on GitHub](https://github.com/intergrav/vital) so that you can easily view what's being changed, contribute if you would like to, or fork the modpack to create your own project. If you would like to view the mods shipped with Vital, simply look at the dependencies in the Modrinth page or look in the Git repository.

# ✅ Hardware Compatibility

Vital supports the use of graphics cards with drivers that are compatible with OpenGL 4.6. Most graphics cards released in 2010 or later are compatible. This includes the following hardware:

- Intel HD Graphics 500 Series (Skylake) or newer
- Nvidia GeForce 400 Series (Fermi) or newer
- AMD Radeon HD 7000 Series (GCN 1) or newer

In some cases, older graphics cards may also work (as long as they have drivers which support OpenGL 3.3) but they are not officially supported and may not be compatible in the future.

Android devices that use OpenGL translation layers (such as GL4ES, ANGLE, etc) are not supported and will likely not work with Vital's set of mods. These translation layers do not implement required functionality and suffer from underlying driver bugs which cannot be worked around.

If you are running into problems, you should make sure that your graphics drivers are up-to-date. I also recommend taking a look at [this page](https://github.com/CaffeineMC/sodium-fabric/wiki/Driver-Compatibility) on the Sodium wiki.

*The majority of this was taken from Sodium's hardware compatibility section. I'll update this accordingly if anything is changed.*

# 🐛 How to Report Issues

Experiencing bugs, crashes, or other issues? Feel free to open an issue on the [issue tracker](https://github.com/intergrav/Vital/issues). Be sure to include necessary information like your hardware/software (e.g. GPU and CPU, modpack version and OS) so that it's easier for us to find issues and resolve them.

# ❓ Frequently Asked Questions

For a few frequently asked questions, along with tons of other information, consider visiting the [wiki](https://github.com/intergrav/Vital/wiki). It has a few other helpful resources that I suggest you read, such as troubleshooting info and more. This wiki is often updated with new information.

# 🍉 Sponsor

Need a fast, reliable Minecraft server? Feel free to use my code `devin` for 25% off your first month of any server from Bisect Hosting, supporting me in the process. Click this banner for more information. You can also setup my server-side performance pack called [Adrenaserver](https://modrinth.com/modpack/adrenaserver) to improve your server's optimization while still allowing vanilla clients to join.

[![Bisect Hosting Image](https://www.bisecthosting.com/partners/custom-banners/444cf491-d49c-4b9a-8b2d-250593122b7e.webp)](https://www.bisecthosting.com/devin)
