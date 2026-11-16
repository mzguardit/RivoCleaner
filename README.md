# RivoCleaner by MZGuard

**Safe Windows cleaner, registry fixer, and smart uninstaller for Windows 10 & Windows 11.**

RivoCleaner frees disk space, fixes registry leftovers, updates outdated apps, and uninstalls programs completely—always showing exactly what it will touch, backing up before modifying the registry, and sending deleted files to the **Recycle Bin**.

🌐 **Official Page & Download:** [mzguard.com/rivocleaner.html](https://mzguard.com/rivocleaner.html)  
🌍 **Languages:** English & Italiano

---

## Core Philosophy: Remove Only What Is Safe

- **Analyze First, Delete Later:** Every item displays its category, size, and file count before anything is touched.
- **Recycle Bin Protection:** Cleaned files and leftovers are sent to the Recycle Bin rather than wiped irreversibly.
- **Automatic Registry Backups:** Every registry cleanup or leftover fix creates a `.reg` backup first.
- **Clear Reporting:** After cleaning, RivoCleaner reports exactly how much space was freed (KB/MB), item by item.

---

## Screenshots

<!-- Sostituisci con i link alle immagini su mzguard.com se disponibili -->
<!-- ![RivoCleaner Main Window](https://mzguard.com/rivocleaner/screenshot.png) -->

---

## Key Features

### 🧹 System & Browser Cleaner
- Cleans Windows, File Explorer, system temporary files, and caches for **Edge, Chrome, Firefox, Brave, Vivaldi, Opera**, and more.
- Collapsible groups with real application icons, selection counters (e.g., `5/11`), and separate **Windows** / **Applications** tabs to keep the list tidy.

### 🗑️ Smart Uninstaller (with Leftover Scan)
- Right-click any installed program to uninstall it, then scan for leftover files and registry keys using strict safety rules:
  - **Exact-name matching**
  - **Protected system locations**
  - **Certain vs. Probable** leftover classification
  - **Recycle Bin & `.reg` backup** before removal

### 🛠️ Registry Cleaner
- Identifies and repairs safe registry leftovers with an automatic `.reg` backup prior to every change.

### 🔁 Software Updater (`winget`)
- Detects outdated applications and updates them silently through **winget**.
- Displays current and target versions side by side, with an **importance indicator** so security updates come first.
- One-click bulk update for selected applications.

### 📄 Duplicate Finder
- Finds duplicate files across your drives to help reclaim wasted storage safely.

### 🕒 Tray Mode, Auto-Clean & Scheduling
- **System Tray:** Minimizes cleanly to the notification area (`X` hides in tray by default) and supports launching with Windows straight into the tray.
- **Browser Auto-Clean:** Automatically cleans only your ticked items for a specific browser the moment you close it.
- **Scheduled Cleaning:** Run cleaning daily or on a chosen date/time; if the PC was off, it catches up at startup while safely skipping open browsers.

---

## Requirements
- **OS:** Windows 10 or Windows 11
- **Privileges:** Administrator permissions may be requested for system-level cleaning, registry operations, and certain `winget` software updates.

---

## Part of the MZGuard Suite
Developed by **Vincenzo Chieppa** / [MZGuard](https://mzguard.com/) · [github.com/mzguardit](https://github.com/mzguardit)
