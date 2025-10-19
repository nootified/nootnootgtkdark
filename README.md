# 🐧 NootNootGTK · Dark Theme

A custom sleek and modern dark GTK theme inspired by the infamous Noot Noot meme.

![NootNoot Meme](https://github.com/nootified/nootnootgtkdark/blob/main/images/meme.gif)

<br>

## 🎨 Features

- Custom dark, elegant color palette
- macOS-style titlebar decorations by [Arnis K](https://github.com/kem-a/macos-titlebar)
- Provides a clean and consistent look across GTK applications

<br>

## 📸 Screenshots

![Preview1](https://github.com/nootified/nootnootgtkdark/blob/main/images/Showcase1.png)

![Preview1](https://github.com/nootified/nootnootgtkdark/blob/main/images/Showcase2.png)

<br>

## 📦 Installation

1. Backup your current GTK config (REQUIRED)
   ```sh
   mv ~/.config/gtk-3.0 ~/.config/gtk-3.0.backup
   mv ~/.config/gtk-4.0 ~/.config/gtk-4.0.backup
   ```
2. Clone this repository:
   ```sh
   git clone https://github.com/nootified/nootnootgtkdark.git nootnootgtkdark
   ```
3. Copy the GTK configuration files from the cloned repo to your `.config` directory:
   ```sh
   mkdir -p ~/.config/gtk-3.0
   cp -r nootnootgtkdark/gtk3.0/* ~/.config/gtk-3.0/

   mkdir -p ~/.config/gtk-4.0
   cp -r nootnootgtkdark/gtk4.0/* ~/.config/gtk-4.0/
   ```
4. Log out and log back in to apply the theme changes properly.

<br>

## 🛠️ To-Do

- Menus (context-menu, hamburger-menu) currently have a fully black background — needs either:
    - Better contrast via background color adjustments
    - Or visible borders to distinguish menu areas

✨ More tweaks and polish coming soon!

<br>

## 🧩 Credits

This theme builds on the work of the following open-source projects:

- [kem-a/macos-titlebar](https://github.com/kem-a/macos-titlebar)  
  Provides the macOS-style titlebar for GTK apps.

- [Rewaita](https://github.com/SwordPuffin/Rewaita)  
  Base theme used for color schemes and GTK styling.
