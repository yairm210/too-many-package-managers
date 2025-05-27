## TOO MANY PACKAGE MANAGERS

There are TOO MANY ways to distribute games and apps. Here's an overview of those I know.


### Android

| Name    | Platforms | Cost | Delivery | Translateable entries? |
| -------- | ------- | --- | --- | --- | 
| [Google Play](https://play.google.com/) | Android | 25$ per account | Automatable | Yes |
| [F-droid](https://f-droid.org) | Android | Free | [Automatable, Self-built](https://monitor.f-droid.org/builds "F-Droid has its own builds and its own release schedule, it recognizes Fastlane data in your repo to trigger builds") | Yes |

### Desktop, Cross-OS

| Name    | Platforms | Cost | Delivery | Translateable entries? |
| -------- | ------- | --- | --- | --- | 
| [Itch.io](https://itch.io/)  | Linux, Windows, MacOS | Free | [Automatable](https://itch.io/docs/butler/) | No | 
| [Steam](https://store.steampowered.com/) | Linux, Windows, MacOS | 100$ per app | [Semi-automatable](## "You can automate uploading to non-release tracks, but release tracks require manual intervention") | Yes | 
| [Homebrew](https://github.com/Homebrew/brew/) | Linux, MacOS | Free | automateable - [example](https://github.com/yairm210/Unciv/blob/a11c3c42163684cce726462f995e7af9553c36bd/.github/workflows/buildAndDeploy.yml#L372) | No | 

### Windows Only

| Name    | Platforms | Cost | Delivery | Translateable entries? |
| -------- | ------- | --- | --- | --- | 
| [Chocolatey](https://chocolatey.org/) | Windows | Free | Automatable | No |
| [Microsoft Store](https://apps.microsoft.com) | Windows | 18$ per account + [CA signing costs](## "Section 10.2.9 of Microrosft store policies - https://learn.microsoft.com/en-us/windows/apps/publish/store-policies - requires a CA signed to a trusted root, which costs money per release")  | ??? | Yes |
| [Scoop](https://scoop.sh/) | Windows | Free | Automatable | No |

### Other


| Name    | Platforms | Cost | Delivery | Translateable entries? |
| -------- | ------- | --- | --- | --- | 
| [MacPorts](https://ports.macports.org/) | MacOS | Free | [Self-built](https://ports.macports.org/all_builds/ "I'm not entirely sure how MacPorts decides when to build") | No |
| [AUR](https://aur.archlinux.org/packages) | Arch Linux | Free | [Automatable, Self-built](## "The AUR PKGBUILD can be updated via CD, the package itself will be built by AUR") | No |
| [Flathub](https://flathub.org/) | Linux | Free | Automatable | No |
| [Snapcraft](https://snapcraft.io/store) | Linux | Free | Automatable | No |
| [Pi-Apps](https://pi-apps.io/) | Raspberry Pi | Free | Automatable | No |
