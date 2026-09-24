# Trap Gnomes V1

A private mod menu for Burglin' Gnomes. Access requires a license key from the owner.

> **This is not free/open software.** Personal use only, and only with a valid key.
> Do not share, re-upload, or pass your key to anyone. See `LICENSE.txt`.

---

## Install

You need the game with **BepInEx** already installed.

1. Download **`GnomeCheats.dll`** from the [latest release](../../releases/latest).
2. Put it in your game's `BepInEx\plugins` folder:
   ```
   Steam\steamapps\common\Burglin' Gnomes\BepInEx\plugins\
   ```
3. Start the game.
4. Press **F1** (the default menu key — you can change it later, see [Keybinds](#keybinds)).
   - If you're already licensed, the menu opens.
   - Otherwise a small box appears — paste your **license key** and click **Activate**.
     You only do this once; it's remembered after that.

> Tip: press **Esc** (the game's pause menu) first so you have a mouse cursor to click with.

---

## Getting a key

Keys are handed out by the owner. Each key is tied to a role:

| Role | What you get |
|------|--------------|
| **Free Version** | FOV, Third Person, Performance Mode, On-Screen Info, Middle Finger, player list, keybinds |
| **Customer** | the above + Infinite Stamina, Unbreakable Limbs, Silent Movement, Immunity, NPC/Item ESP, Gnome Customization |
| **Admin** | everything (God Mode, Speed, No Clip, Moon Boots, Player ESP/Info, Player Inventory ESP, Teleport, spawners, Host tools) |

If a feature shows `[Admin]` or `[Customer]` next to it and is greyed out, your key's role
doesn't include it yet — ask the owner about an upgrade.

---

## Keybinds

**Menu Settings → Keybinds.** Click a key box, then press the key (or extra mouse button) you
want. Esc cancels.

- Only the mods your role can use are listed.
- The menu key can be changed but never removed, so you can't lock yourself out.
  **Reset all keybinds** puts it back to F1.
- Hotkeys don't fire while you're typing, and a small popup shows ON/OFF when one does.
- Your keybinds are saved between launches.

---

## Gnome Customization

*Customer role and up.* **Player tab → Gnome Customization** opens its own window:

- Pick a part of your gnome on the left, then a colour on the right: palette, hue/saturation/brightness
  sliders, **Solid colour**, **Rainbow**, or a one-click **Outfit**.
- The middle shows your gnome live. Drag it (or use **Spin**) to see it from every side; scroll to zoom.
- **Save & Exit** keeps your look (it's remembered between launches); **Back** throws the changes away.
- **Custom look: ON/OFF** switches back to the normal gnome without losing your colours.
  **Reset Gnome** clears your look completely.

**Who sees it:** everyone in your lobby who also has the mod sees your look — and your Middle
Finger — on your gnome, and you see theirs. While you're in the customizer they watch your changes
live; press **Back** and your gnome goes back to your saved look for them too. It only ever changes
the gnome of the person who set it. Players without the mod see the normal gnome.

---

## Updates

When a newer version is out, the menu shows a green **"Update available"** notice with a
**Download** button. Click it, grab the new `GnomeCheats.dll` from the releases page, and
replace the old one in your `plugins` folder. The mod never replaces itself automatically.

---

## Notes

- Your key can be turned off by the owner at any time.
- Don't run this in public lobbies with strangers — it's meant for private games with friends.
  Sharing your look with other mod users works through the Steam lobby, so anyone in the lobby
  with the right tools could tell you're running a mod.
