> [!WARNING]  
> This is an archive of the code pushed during my time at Administer. I simply made it because I was unhappy with what was happening in [upstream](https://github.com/administer-org/administer) by the new owner. 
> 
> If you are looking to download modern "v1" Administer, go there. However, if you want the unmaintained-but-will-still-work-with-AOS 2.2.0 link, here is a conveniently placed [download link for my model](https://create.roblox.com/store/asset/127698208806211). For era-appropriate AOS along with a dump of the apps database please visit [pyxfluff/administer-aos](https://github.com/pyxfluff/administer-aos). Unfortunately the new owner does not seem to believe in open source like I do but forks of this repository and 2.2.0 are still welcome. I don't know what's happening with the rest of the repositories, I can only make so much change happen under new leadership. I have tried fighting for the best but all I ever get back is excuses and unkept promises.
>
> Due to lack of compliance I shut down existing web services, so old stuff 2.2.0 relied on such as the Router are unreliable at best and [should be forked](https://github.com/administer-org/router) for personal use. However we only ran stuff that was open source (Weblate, Plausible, etc) or created stuff that was so you can 100% duplicate the old infrastructure if you would like. When a repository is updated, if I'm unhappy with a change made I'll push a 2.2.0-era repository to my account too.
>
> \- Sincerely, an old project manager who still cares 🫡

<div align="center">
 
![Administer|65%](/.readme/Administer-Text.png)

# Simple & Open Administration

[![pyxfluff - administer](https://img.shields.io/static/v1?label=pyxfluff&message=administer&color=blue&logo=github)](https://github.com/pyxfluff/administer "Go to GitHub repo") [![stars - administer](https://img.shields.io/github/stars/administer-org/administer?style=social)](https://github.com/pyxfluff/administer) [![forks - administer](https://img.shields.io/github/forks/administer-org/administer?style=social)](https://github.com/pyxfluff/administer) [![translation status](https://translate.admsoftware.org/widget/administer/svg-badge.svg?native=1)](https://translate.admsoftware.org)

[![License](https://img.shields.io/badge/License-GNU--AGPL--3.0-blue)](#license) [![issues - administer](https://img.shields.io/github/issues/pyxfluff/administer)](https://github.com/pyxfluff/administer/issues) [![Hits-of-Code](https://hitsofcode.com/github/pyxfluff/administer?branch=main)](https://hitsofcode.com/github/pyxfluff/administer/view?branch=main)


### [Install from Roblox](https://create.roblox.com/store/asset/127698208806211/Administer) · [DevForum Topic](https://devforum.roblox.com/t/administer-modern-modular-free-admin-system-12/3179989) · [Development Trello](https://trello.com/b/GA5Kc0vB/administer) · [Documentation](https://docs.admsoftware.org)

</div>

## What is it?

Administer is a next-generation admin system for Roblox which features modularity, granular permissions, a community-powered App Marketplace, and more.


## Installation

### 1. Get the model
You can get the latest release [on Roblox.](https://create.roblox.com/store/asset/127698208806211/Administer)

### 2. Make sure the game can run Administer properly:
You **must** enable the following permissions in your game for Administer to function. Everything can be found in Game Security settings.
- Studio APIs (for saving data and initializing settings, admins, apps, etc)
- HTTP Requests (for communicating with app servers)

(Optionally, Image APIs for rendering some nice looking blur effects)

### 3. Move to the correct location
Move Administer to ServerScriptService. If you would like, this is where you can hardcode admins inside of the Core/Configuration module. Please do not change any settings in this module.

### 4. Configure admins and settings
Enter the game and you should be greeted with the onboarding wizard, where you can configure your new Administer installation. Have fun!

## Custom commands & apps
Please read [our documentation.](https://docs.admsoftware.org) You'll be able to find video and text tutorials on Administer APIs, basic concepts, and advanced modification of the system.

## Contributions

Contributions are more than welcome and will be reviewed within a couple business days. We use Rojo so it's an easy sync (given you have the proper setup). Please read the CONTRIBUTING file at the top of the README.

Feeling nice? Add a feature from [our development priorities.](https://trello.com/b/GA5Kc0vB/administer) Want to fix a bug? Just push the fix. 

If you're adding a new feature, you may want to open an issue before coding something. We may deny PRs if it does not contribute to the project in a way an app can't. If you want an app on the main app server please [reach out to us](https://administer.notpyx.me/to/discord).

## Credits

Administer is owned and maintained by [@pyxfluff](http://github.com/pyxfluff).

We utilize many other open-source resources such as:
- UICons: FlatIcon
- QuickBlur: [@pixe_ated](https://devforum.roblox.com/u/pixe_ated)
- neon: [@fractality](https://devforum.roblox.com/u/fractality)

---

<a href="https://translate.admsoftware.org/engage/administer/">
<img src="https://translate.admsoftware.org/widget/administer/user-guide/multi-auto.svg" alt="Translation status" />
</a>

&copy; pyxfluff 2024 - 2025 &bullet; Usage of Administster or its code is governed under the GNU AGPL 3.0 License.

