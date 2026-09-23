   **This is A List of GSIs which is similar to phhusson's GSI list which was Archived, This List Has The Android GSIs Released With Android 16 and Android 17**

*THIS REPOSITORY USES THE CODE FROM ReeMos-GSI's REPOSITORY*

*THIS GITHUB ACCOUNT'S OWNER IS ALSO THE OWNER OF ReeMos-GSI's Github ACCUONT

*Please View Notes.md For Important Warnings*

*Links below are cross-checked against the actively-maintained [TrebleDroid GSI wiki](https://github.com/TrebleDroid/treble_experimentations/wiki/Generic-System-Image-(GSI)-list) (the community successor to phhusson's archived list). Entries that were pointing at dead tags, wrong maintainers, or stale releases have been corrected.*

## How to Choose a GSI

- **GMS vs Vanilla**: GMS includes Google Play Services for apps and updates, Vanilla is pure Android. Most third-party projects below publish both — check the filenames on the linked release page (e.g. `_gms` / `_gapps` vs `_vanilla` / no suffix).
- **Architecture**: ARM64-AB/ARM64-B (64-bit modern), x86_64 (rare, mostly emulators), ARM32-BINDER64 (for devices with >3GB RAM using 32-bit binder)
- **QPR**: Quarterly Platform Release - security updates and improvements. Higher QPR = newer, but also less tested if it's still in Beta
- **Maintainer**: Different projects offer different customizations; Google GSI is the official baseline
- **EOL/Archived**: Tagged builds are no longer updated by their maintainer — they still work, but won't get further security patches

## Quick Links

- [Android 17 GSIs](#android-17-gsis)
- [Android 16 GSIs](#android-16-gsis)
- [Android 15 GSIs](#android-15-gsis)
- [Android 14 GSIs](#android-14-gsis)
- [Android 13 GSIs](#android-13-gsis)
- [Android 12 GSIs](#android-12-gsis)

### Android 17 GSIs

Android 17 is still in Developer Preview/Beta as of this update — Google's official GSIs are the only trustworthy option right now. No third-party (custom ROM) GSIs have a stable public release yet; the few that exist are early experimental single-developer builds without proper release artifacts, so they're intentionally left off this list until they mature.

| GSI Name | Maintainer | Android Version | Download Link | Architecture | GMS or Vanilla |
| --- | --- | --- | --- | --- | --- |
| **Google GSI (QPR2 Beta)** | Google | 17.0 QPR2 Beta | [Android Developers](https://developer.android.com/about/versions/17/qpr2/gsi-release-notes) | ARM64, x86_64 | Both Available |
| **Google GSI (QPR1 Beta)** | Google | 17.0 QPR1 | [Android Developers](https://developer.android.com/about/versions/17/qpr1/gsi-release-notes) | ARM64, x86_64 | Both Available |
| **Google GSI (Initial)** | Google | 17.0 | [Android Developers](https://developer.android.com/about/versions/17/gsi-release-notes) | ARM64, x86_64 | Both Available |

### Android 16 GSIs

| GSI Name | Maintainer | Android Version | Download Link | Architecture | GMS or Vanilla |
| --- | --- | --- | --- | --- | --- |
| **Google GSI** | Google | 16.0 (Current QPR) | [Android Developers](https://developer.android.com/about/versions/16/gsi-release-notes) | ARM64, x86_64 | Both Available |
| **BestGSI** | Amintum | 16.0 | [GitHub](https://github.com/amintum/BestGSI/releases/latest) | ARM64 | Both Available |
| **Infinity X** | Doze-off | 16.0 | [GitHub](https://github.com/Doze-off/ProjectInfinity-X_gsi/releases/latest) | ARM64 | Both Available |
| **AxionOS** | Doze-off | 16.0 | [GitHub](https://github.com/Doze-off/axion_aosp/releases/latest) | ARM64 | Both Available |
| **AxionOS 2.7 (alt. build)** | itisFarzin | 16.0 | [GitHub](https://github.com/itisFarzin/AxionOS_GSI/releases/tag/AxionOS-2.7-20260711) | ARM64 | Both Available |
| **Project CiRCLE** | Doze-off | 16.0 | [GitHub](https://github.com/Doze-off/Project-CiRCLE_gsi/releases/latest) | ARM64 | Both Available |
| **Evolution X** | Doze-off | 16.0 | [GitHub](https://github.com/Doze-off/EvoX_treble/releases) | ARM64 | GMS Only |
| **DerpFest** | Doze-off | 16.0 | [GitHub](https://github.com/Doze-off/Derpfest_treble/releases) | ARM64 | GMS Only |
| **Lineage OS 23.2** | MisterZtr | 16.0 | [GitHub](https://github.com/MisterZtr/LineageOS_gsi/releases/tag/v2026.05.24-lineage23.2) | ARM64 | Both Available |
| **VoltageOS** | Doze-off | 16.0 | [GitHub](https://github.com/Doze-off/voltage_a16_treble/releases) | ARM64 | Both Available |
| **SuperiorOS** | Doze-off | 16.0 | [GitHub](https://github.com/Doze-off/SuperiorOS_treble/releases/tag/2026-05-31) | ARM64 | Both Available |
| **crDroid** | Doze-off | 16.0 | [GitHub](https://github.com/Doze-off/crdroid_gsi_treble/releases) | ARM64 | Both Available |
| **PixelOS** | Doze-off | 16.0 | [GitHub](https://github.com/Doze-off/PixelOS_GSI_treble/releases) | ARM64 | GMS Only |
| **Project Sakura** | Doze-off | 16.0 | [GitHub](https://github.com/Doze-off/ProjectSakura_gsi/releases) | ARM64 | Both Available |
| **AICP** | Doze-off | 16.0 | [GitHub](https://github.com/Doze-off/AICP_treble/releases) | ARM64 | Both Available |
| **YAAP** | Doze-off | 16.0 | [GitHub](https://github.com/Doze-off/YAAP_treble/releases/latest) | ARM64 | Both Available |
| **Clover** | Doze-off | 16.0 | [GitHub](https://github.com/Doze-off/Clover_treble/releases) | ARM64 | Both Available |
| **RestlessOS (GrapheneOS-based)** | cawilliamson | 16.0 | [GitHub](https://github.com/cawilliamson/treble_grapheneos/releases/latest) | ARM64 | Vanilla Only |
| **eOS 4.3 (/e/OS)** | Colors / Murena | 16.0 | [SourceForge](https://sourceforge.net/projects/e-os/files/GSI/16/) | ARM64 | Vanilla Only |

### Android 15 GSIs

| GSI Name | Maintainer | Android Version | Download Link | Architecture | GMS or Vanilla |
| --- | --- | --- | --- | --- | --- |
| **Google GSI** | Google | 15.0 | [Android Developers](https://developer.android.com/about/versions/15/gsi-release-notes) | ARM64, x86_64 | Both Available |
| **eOS 4.3 (/e/OS)** | Colors / Murena | 15.0 | [SourceForge](https://sourceforge.net/projects/e-os/files/GSI/15/) | ARM64 | Vanilla Only |
| **crDroid 11.17** | anna-adnana | 15.0 | [SourceForge](https://sourceforge.net/projects/crdroidos/files/GSI/) | ARM64 | Both Available |
| **LineageOS 22.2** | MisterZtr | 15.0 | [GitHub](https://github.com/MisterZtr/LineageOS_gsi/releases/tag/v2026.01.05-lineage22.2) | ARM64 | Both Available |
| **AOSP** | TrebleDroid Builders | 15.0 | [GitHub](https://github.com/TrebleDroid/treble_experimentations/releases) | ARM64-Binder | Vanilla Only |
| **PixelOS** | mytja | 15.0 | [GitHub](https://github.com/mytja/treble_pixelos/releases/tag/20250517) | ARM64 | GMS Only |
| **Evolution X** | mytja | 15.0 | [GitHub](https://github.com/mytja/treble_evo/releases/tag/20250421) | ARM64 | GMS Only |
| **KLC OS** | Kanagawa Yamada | 15.0 | [GitHub](https://github.com/LoggingNewMemory/KLC_OS/releases) | ARM64 | Both Available |
| **Miku UI** | yukineko2233 | 15.0 | [GitHub](https://github.com/yukineko2233/treble_build_miku/releases) | ARM64 | Both Available |
| **SuperiorOS** *(End of Life)* | Doze-off | 15.0 | [GitHub](https://github.com/Doze-off/SuperiorOS_treble/releases/tag/2025-06-10) | ARM64 | Both Available |

### Android 14 GSIs

*Android 14 is now legacy — most GSIs here are archived or end-of-life and no longer receive security updates. Kept for reference for older devices still on this branch.*

| GSI Name | Maintainer | Android Version | Download Link | Architecture | GMS or Vanilla |
| --- | --- | --- | --- | --- | --- |
| **Google GSI** | Google | 14.0 | [Android Developers](https://developer.android.com/about/versions/14/gsi-release-notes) | ARM64, x86_64 | Both Available |
| **AOSP** | TrebleDroid Builders | 14.0 | [GitHub](https://github.com/TrebleDroid/treble_experimentations/releases/tag/ci-20240508) | ARM64-Binder | Vanilla Only |
| **Project Elixir** | UniversalX | 14.0 | [Project site](https://projectelixiros.com/device/gsi) | ARM64 | Both Available |
| **DerpFest** | KoysX | 14.0 | [GitHub](https://github.com/KoysX/treble_DerpFest_GSI/releases) | ARM64 | GMS Only |
| **Evolution X** | Ahnet | 14.0 | [GitHub](https://github.com/ahnet-69/treble_evo/releases) | ARM64 | GMS Only |
| **HorizonDroid** | Braia | 14.0 | [SourceForge](https://sourceforge.net/projects/braiagsi/files/HorizonDroid/) | ARM64 | GMS Only |
| **Evolution XYZ** | ngankbka | 14.0 | [GitHub](https://github.com/ngankbka/treble_evolution/releases/) | ARM64 | GMS Only |
| **Project Sakura** *(Archived)* | ChonDoit | 14.0 | [GitHub](https://github.com/ChonDoit/treble_sakura_patches/releases) | ARM64 | Both Available |
| **ImbrogliOS** *(End of Life)* | imbroglius | 14.0 | [GitHub](https://github.com/imbroglius/imbroglios_gsi/releases/tag/v2024.08.18) | ARM64 | Both Available |
| **PixelOS** *(Archived)* | MisterZtr | 14.0 | [GitHub](https://github.com/MisterZtr/PixelOS_gsi/releases) | ARM64 | Both Available |
| **Voltage OS** *(End of Life)* | cawilliamson | 14.0 | [GitHub](https://github.com/cawilliamson/treble_voltage/releases/) | ARM64, BINDER64 | Both Available |
| **AOSP** *(End of Life)* | ponces | 14.0 | [GitHub](https://github.com/ponces/treble_aosp/releases) | ARM64 | Both Available |
| **EverestOS** *(End of Life)* | kaii-lb | 14.0 | [GitHub](https://github.com/kaii-lb/treble_manifest/releases/tag/v1.3) | ARM64 | GMS Only |

*Note: iodéOS, RisingOS, and LeafOS remain excluded from this section per Notes.md (source files removed / source not trusted at the time of review).*

### Android 13 GSIs

| GSI Name | Maintainer | Android Version | Download Link | Architecture | GMS or Vanilla |
| --- | --- | --- | --- | --- | --- |
| **Google GSI** | Google | 13.0 | [Android Developers](https://developer.android.com/about/versions/13/gsi-release-notes) | ARM64, x86_64 | Both Available |
| **AOSP** | TrebleDroid Builders | 13.0 | [GitHub](https://github.com/TrebleDroid/treble_experimentations/releases) | ARM64-Binder | Vanilla Only |
| **Pixel Experience** | ponces | 13.0 | [GitHub](https://github.com/ponces/treble_build_pe/releases) | ARM64-AB | GMS Only |
| **Project Elixir** | KrutosX & Lynix | 13.0 | [Pling](https://www.pling.com/p/1960767/) | ARM64 | Both Available |
| **DerpFest** | KoysX | 13.0 | [GitHub](https://github.com/KoysX/treble_DerpFest_GSI/releases) | ARM64 | GMS Only |
| **crDroid** | naz664 | 13.0 | [GitHub](https://github.com/naz664/crDroid_gsi/releases) | ARM64-Binder | Both Available |
| **Evolution X** | ponces | 13.0 | [GitHub](https://github.com/ponces/treble_build_evo/releases/tag/v2023.09.14) | ARM64 | GMS Only |
| **AlphaDroid** | ChonDoit | 13.0 | [GitHub](https://github.com/ChonDoit/treble_alphadroid_patches/releases/tag/A13-v20231009) | ARM64 | Both Available |
| **SuperiorOS** | ChonDoit | 13.0 | [GitHub](https://github.com/ChonDoit/treble_superior_patches/releases/tag/A13) | ARM64 | Both Available |

### Android 12 GSIs

| GSI Name | Maintainer | Android Version | Download Link | Architecture | GMS or Vanilla |
| --- | --- | --- | --- | --- | --- |
| **AOSP** | Google | 12.0/12L | [AOSP CI](https://ci.android.com/builds/branches/aosp-android12-gsi/grid) | ARM64, x86_64 | Vanilla Only |
| **AOSP 12.1** | phhusson | 12.1 | [GitHub](https://github.com/phhusson/treble_experimentations/releases) | ARM64-Binder | Vanilla Only |
| **Corvus OS** | TipzTeam2 | 12.0 | [SourceForge](https://sourceforge.net/projects/tipzbuilds/files/GSIs/CorvusROM/Unofficial/20221008/) | ARM64 | Both Available |
| **LineageOS 19.1** | AndyYan | 12.1 | [SourceForge](https://sourceforge.net/projects/andyyan-gsi/files/lineage-19.x/) | ARM64-Binder | Vanilla Only |
| **SuperiorOS** | ChonDoit | 12L | [GitHub](https://github.com/ChonDoit/treble_superior_patches/releases/tag/A12L) | ARM64 | Both Available |
| **crDroid** | Nazim | 12.1 | [SourceForge](https://sourceforge.net/projects/gsi-projects/files/A12.1/crDroid-8.10/16102022/) | ARM64-Binder | Both Available |
| **Arrow OS** | Nazim | 12.1 | [SourceForge](https://sourceforge.net/projects/gsi-projects/files/A12.1/ArrowOS-12.1/19102022/) | ARM64-Binder | Both Available |
| **StatiXOS** | StatiX Team | 12.0 | [Project site](https://downloads.statixos.com/12-GSI/) | ARM64 | GMS Only |
| **DescendantOS** | Dil3mm4 | 12.0 | [Project site](https://downloads.descendant.me/) | ARM64 | Both Available |