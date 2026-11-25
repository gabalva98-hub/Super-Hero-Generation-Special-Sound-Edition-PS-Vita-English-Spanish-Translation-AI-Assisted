# Super Hero Generation — English & Spanish Fan Translation

An unofficial, free English and Latin American Spanish fan translation of **Super Hero Generation: Special Sound Edition** for **PS Vita**, presented by **Gyasuke & Wakabayashy Workshop**.

The translation is distributed through an **offline HTML patcher**. The game is not included: you must provide your own original files from the supported Japanese edition.

**Build:** 0.7.0 V060  
**Supported edition:** Japanese Special Sound Edition — **PCSG00440**  
**Translation languages:** English and Latin American Spanish  
**Patcher interface languages:** English and Spanish, independent of the selected game language.

**Required files:** both must come from the **base game without updates**, with its folder opened using **Open decrypted in VitaShell** before copying. This applies to both fixed.cpk and eboot.bin.

## What's included

- English and Spanish translations of all 79 extracted story files: 9,564 dialogue entries per language.
- All 260 catalog biographies translated in both languages.
- Translated character, unit and attack names, objectives, descriptions, and other interface text, with ongoing terminology and consistency review.
- Translated originally Japanese graphics. Graphics that were already in English remain in English.
- Font adjustments, improved word spacing, and Spanish characters.
- A ready-to-copy rePatch folder containing the CPK and executable for the selected translation language.
- Local processing: your files are not uploaded to a server.

**The translation remains under review.** Completing the extracted story and biographies does not mean every interface, image, or variation has received final verification.


V058 adds chapter titles in both languages, completes all 61 hero quests in Spanish, and makes attack names consistent between text and graphics. It also translates music-list labels and quest-reward wording. Organization proper names are retained.

V059 adds 59 map-notification and upgrade-badge labels in both languages. V060 fixes clipping by fitting text within the actual regions sampled by the animations: 30 English and 32 Spanish textures, including the Spanish deployment banner. Chapter titles were also checked. Original texture dimensions and animations are preserved. The new adjustments still require visual confirmation on a real PS Vita.

## Installation

1. Back up your original game files and save data.
2. Extract the patcher package and open **SHG_VITA_PARCHEADOR_PUBLICO_EN_ES_V060.html** in an up-to-date compatible browser on a computer or Android device.
3. Obtain **fixed.cpk and eboot.bin from the Japanese base game without updates**. In VitaShell, open the base-game folder using **Open decrypted**, then copy both files from that view. Do not use files from the update folder or previously patched files. Select those two copies in the patcher.
4. Choose **English** or **Español latinoamericano** under **Translation language**. **Interface language** only changes the patcher's own text.
5. Select **Create rePatch** and wait for the ZIP to be prepared. Keep the browser open and allow enough free storage for the original files, the ZIP, and the extracted output.
6. Extract the generated ZIP. Copy its **rePatch** folder to **ux0:** so the files are located at:
   - `ux0:rePatch/PCSG00440/fixed.cpk`
   - `ux0:rePatch/PCSG00440/eboot.bin`
7. With **rePatch installed and enabled** on your PS Vita, launch the game normally.

If the original `fixed.cpk` is inside a game subfolder, retain that path under **Advanced** before generating the ZIP. If it is in the game's root folder, leave the default `fixed.cpk` path unchanged.

**Important:** always start with the original Japanese files, never an already modified CPK or executable. Releases are cumulative; earlier patches do not need to be applied first. Replace both the CPK and executable from the previous version together.

## Compatibility and testing

**Gameplay testing has been performed exclusively on a real PS Vita. Emulator compatibility has not been tested.**

The patcher supports the **Japanese Special Sound Edition, PCSG00440**. It is not prepared for other editions or title IDs.

File checks and patcher validation do not replace a complete in-game review. The latest biographies and other changes still need thorough visual verification on hardware. Not every route, optional scene, or battle combination has been tested.

## Known limitations and bug reports

- Some interface text may still appear in English or Japanese, particularly in the Spanish version.
- Translation errors, inconsistent terminology, clipped text, or alignment issues may remain.
- Originally English graphics are intentionally kept in English.

When reporting a problem, include the patch build, selected language, affected mission or screen, and steps to reproduce it. A screenshot or short video helps identify the issue. Back up your save before attempting to reproduce a bug.

**Do not include game files in bug reports.**

## Credits

**Project and presentation:** Gyasuke & Wakabayashy Workshop.

## Distribution

This is an **unofficial, non-commercial fan translation**. It is not affiliated with or endorsed by Bandai Namco or any original rights holder. The game, characters, music, and trademarks belong to their respective owners.

**The patch is free. It must not be sold or placed behind a paywall. If you paid for it, you were scammed; the project does not authorize anyone to charge for this patch.**

No game copies, BIOS files, or original executables are distributed. You must provide your own game files.

---

Thank you for playing Super Hero Generation in English or Spanish!
