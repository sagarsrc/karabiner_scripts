# ⌨️ Karabiner Shortcuts Collection

A curated collection of keyboard shortcuts and remappings for enhanced productivity.

---

## 🔑 CAPS LOCK REMAPPING
**Files:** `rename_caps_lock_to_super.json` / `remap_caps_lock_shift_super.json`

| From | To | Description |
|------|-----|-------------|
| `⇪ Caps Lock` | `⌃⇧⌥⌘` Super | Caps Lock becomes Super key (Ctrl+Shift+Option+Command) |

---

## 🚀 APPLICATION SHORTCUTS
**File:** `app_launchers.json`

| Shortcut | Action |
|----------|--------|
| `⇪ Caps Lock` + `G` | Open/switch to **Google Chrome** |
| `⇪ Caps Lock` + `B` | Open/switch to **Brave Browser** |
| `⇪ Caps Lock` + `D` | Open/switch to **Cursor** |
| `⇪ Caps Lock` + `T` | Open/switch to **Warp** |
| `⇪ Caps Lock` + `C` | Open/switch to **Claude** |
| `⇪ Caps Lock` + `W` | Open/switch to **WhatsApp Web** |
| `⇪ Caps Lock` + `M` | Open/switch to **WhatsApp** |
| `⇪ Caps Lock` + `L` | Clear terminal (sends `⌃ Ctrl` + `L`) |

---

## 🔄 FN KEY REMAPPING
**File:** `fn_to_control.json`

| From | To | Description |
|------|-----|-------------|
| `Fn` (built-in keyboard) | `⌃ Left Control` | Fn key acts as Left Control |

> **Note:** This is a device-level `simple_modifications` entry applied to all keyboards via a generic `"is_keyboard": true` identifier. It uses `apple_vendor_top_case_key_code: keyboard_fn` which is how macOS exposes the Fn key to Karabiner.

---

## 🎯 CONTROL KEY BEHAVIOR
**File:** `remap_escape_to_control.json`

| From | To | Description |
|------|-----|-------------|
| `⌃ Left Control` (pressed alone) | `⎋ Escape` | Control becomes Escape when tapped |
| `⌃ Left Control` (with other keys) | `⌃ Control` | Normal Control function when held |
| `⌃ Right Control` (pressed alone) | `⎋ Escape` | Control becomes Escape when tapped |
| `⌃ Right Control` (with other keys) | `⌃ Control` | Normal Control function when held |

---

## ✨ VIM-STYLE NAVIGATION (hjkl)
**File:** `vim_arrow_keys.json`

### Basic Navigation
| Shortcut | Action |
|----------|--------|
| `⌃ Ctrl` + `H` | `←` Left Arrow |
| `⌃ Ctrl` + `J` | `↓` Down Arrow |
| `⌃ Ctrl` + `K` | `↑` Up Arrow |
| `⌃ Ctrl` + `L` | `→` Right Arrow |

### Word-Level Movement
| Shortcut | Action |
|----------|--------|
| `⌥ Option` + `H` | `⌥ Option` + `←` (Move left by word) |
| `⌥ Option` + `J` | `⌥ Option` + `↓` (Move down by word) |
| `⌥ Option` + `K` | `⌥ Option` + `↑` (Move up by word) |
| `⌥ Option` + `L` | `⌥ Option` + `→` (Move right by word) |

### Line-Level Movement
| Shortcut | Action |
|----------|--------|
| `⌃ Ctrl` + `⌘ Cmd` + `H` | `⌘ Cmd` + `←` (Move to line start) |
| `⌃ Ctrl` + `⌘ Cmd` + `J` | `⌘ Cmd` + `↓` (Move to document end) |
| `⌃ Ctrl` + `⌘ Cmd` + `K` | `⌘ Cmd` + `↑` (Move to document start) |
| `⌃ Ctrl` + `⌘ Cmd` + `L` | `⌘ Cmd` + `→` (Move to line end) |

### Selection (Basic)
| Shortcut | Action |
|----------|--------|
| `⌃ Ctrl` + `⇧ Shift` + `H` | `⇧ Shift` + `←` (Select left) |
| `⌃ Ctrl` + `⇧ Shift` + `J` | `⇧ Shift` + `↓` (Select down) |
| `⌃ Ctrl` + `⇧ Shift` + `K` | `⇧ Shift` + `↑` (Select up) |
| `⌃ Ctrl` + `⇧ Shift` + `L` | `⇧ Shift` + `→` (Select right) |

### Selection (Word-Level)
| Shortcut | Action |
|----------|--------|
| `⌥ Option` + `⇧ Shift` + `H` | `⌥ Option` + `⇧ Shift` + `←` (Select word left) |
| `⌥ Option` + `⇧ Shift` + `J` | `⌥ Option` + `⇧ Shift` + `↓` (Select word down) |
| `⌥ Option` + `⇧ Shift` + `K` | `⌥ Option` + `⇧ Shift` + `↑` (Select word up) |
| `⌥ Option` + `⇧ Shift` + `L` | `⌥ Option` + `⇧ Shift` + `→` (Select word right) |

### Selection (Line-Level)
| Shortcut | Action |
|----------|--------|
| `⌃ Ctrl` + `⌘ Cmd` + `⇧ Shift` + `H` | `⌘ Cmd` + `⇧ Shift` + `←` (Select to line start) |
| `⌃ Ctrl` + `⌘ Cmd` + `⇧ Shift` + `J` | `⌘ Cmd` + `⇧ Shift` + `↓` (Select to document end) |
| `⌃ Ctrl` + `⌘ Cmd` + `⇧ Shift` + `K` | `⌘ Cmd` + `⇧ Shift` + `↑` (Select to document start) |
| `⌃ Ctrl` + `⌘ Cmd` + `⇧ Shift` + `L` | `⌘ Cmd` + `⇧ Shift` + `→` (Select to line end) |

---

## 🗑️ DELETE KEY MAPPINGS
**File:** `custom_delete_mapping.json`

| Shortcut | Action |
|----------|--------|
| `⌃ Ctrl` + `D` | `⌦ Delete` forward (single character) |
| `⌥ Option` + `D` | `⌥ Option` + `⌦ Delete` forward (delete word) |
| `⌃ Ctrl` + `⌘ Cmd` + `D` | `⌃ Ctrl` + `⌘ Cmd` + `⌦ Delete` forward |

---

## 🖱️ MOUSE SHORTCUTS
**File:** `right_shift_mouse_click.json`

| From | To | Description |
|------|-----|-------------|
| `⇧ Right Shift` (pressed alone) | Right Mouse Click | Quick right-click |
| `⇧ Right Shift` (with other keys) | `⇧ Shift` | Normal Shift function |

**File:** `swap_esc_delete.json`

| From | To |
|------|-----|
| `⎋ Escape` | Left Mouse Click |

---

## 📝 IMPORTANT NOTES

**⚠️ Terminal Clear Shortcut**
- `⇪ Caps Lock` + `L` is mapped to clear the terminal
- `⇪ Caps Lock` acts as the **Super key** (`⌃⇧⌥⌘`), so `⇪ Caps Lock` + `L` is essentially `Super` + `L`
- The standard `⌃ Ctrl` + `L` shortcut won't work directly
- Use `⇪ Caps Lock` + `L` instead for clearing the terminal

---

## 🔤 Key Symbols Reference

| Symbol | Key |
|--------|-----|
| `⌘` | Command |
| `⌃` | Control |
| `⌥` | Option/Alt |
| `⇧` | Shift |
| `⇪` | Caps Lock |
| `⎋` | Escape |
| `⌦` | Delete (Forward) |
| `⌫` | Delete (Backward) |
| `←` `→` `↑` `↓` | Arrow Keys |

---

**Made with ❤️ for productivity**
