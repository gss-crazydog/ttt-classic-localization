# TTT Classic Localizations

This repository contains the localization files for **[TTT Classic](https://store.steampowered.com/app/4570530/TTT_Classic/)**. 

We welcome contributions from anyone! If you would like to correct existing translations or add support for a new language, please feel free to submit a pull request.

Anyone who contributes to translations will be included in the thanks section in the README and mentioned in patch notes. If you do NOT want to be mentioned, please mention in your pull requests/issues.
---

## File Structure & Descriptions

Currently, the primary language files are housed inside language-specific directories (such as the `/en` folder for English). Here is what each file/folder corresponds to:

*   **`quickchat/`** – Contains audio files that play when quickchat is used (corresponding directly with translation keys starting with `TTT_QUICK_`). Audio files must be formatted as **8-bit mono WAV at 11.025 kHz (~88 kbps)**.
*   **`achievements.vdf`** – Steam Achievement localizations (located in the root directory, containing all languages).
*   **`rich_presence.vdf`** – Steam Rich Presence localizations (located in the root directory, containing all languages).
*   **`gameui_<language>.txt`** – Stock Half-Life Game UI strings.
*   **`serverbrowser_<language>.txt`** – Stock Half-Life Server Browser strings.
*   **`valve_<language>.txt`** – Stock Half-Life engine/game strings.
*   **`ttt_<language>.txt`** – TTT Classic-specific gameplay and UI strings.
*   **`storepage.json`** – The text used for the Steam Store page listing (located in the root directory).

---

## How to Contribute

We support editing existing language translations or proposing new ones.

### Modifying Existing Translations
1. Locate the language folder or root file you want to edit.
2. Make your corrections/updates to the relevant translation file.
3. Submit a pull request with a brief explanation of the changes.

### Proposing a New Language
If you want to add a language not yet present:
1. Refer to the list of supported Steam languages: [Steam Localization Languages](https://partner.steamgames.com/doc/store/localization/languages).
2. Note the type of language support needed:
    *   **Full Platform** languages should provide localizations for achievements (`achievements.vdf`), rich presence (`rich_presence.vdf`), and `storepage.json`.
    *   **All Other Languages (including ones not supported by Steam!)** are used for all other files (`quickchat/`, `gameui_`, `serverbrowser_`, `valve_`, and `ttt_`).
3. Copy the English keys/files as a baseline, add/translate the text, and submit your pull request!
