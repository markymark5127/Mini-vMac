# 🖥️ Mini vMac Macintosh Plus Setup (macOS 15.5)

This repository contains a ready-to-run **Mini vMac** configuration that emulates a **Macintosh Plus** running System Software 6–7, curated for use on **macOS 15.5**. It’s a nostalgic dive into classic Macintosh software and games, perfect for retro computing fans or introducing kids to vintage Mac fun.

---

## 📦 What's Inside

### 🗃️ Installed on the Virtual Drive:
- **StuffIt Expander** – Unpack classic Mac archives
- **DropStuff DA Piggyback** – Repack files into StuffIt format
- **Font/DA Mover** – Add or remove desk accessories and fonts
- **Import FL** – Import files from your host machine into Mini vMac
- **Disk Copy** – Create and mount Mac disk images
- **ResEdit** – The classic Macintosh resource editor
- **SuperClock** – Adds a clock to the menu bar

---

### 🖥️ Desktop Folders

#### 📁 `Apps`
- **MacPaint** – The legendary bitmap painting program
- **Kid Pix** – A fun drawing app for kids

#### 🎮 `Games`
- **Hangman** – Word guessing classic  
- **MacPong** – Pong-style retro arcade game  
- **Missile** – Missile Command-style gameplay  
- **Dalecks** – Dalek-inspired strategy game  
- **Destroyer** – Action shooter  
- **LodeRunner** – Iconic puzzle-platformer  
- **Mouse** – Maze-style mouse game  
- **Mouse Eaters** – Cat-and-mouse arcade game  
- **Millie's Math House** – Early learning math activities  
- **Bailey's Book House** – Literacy-building educational software

---

## 🚀 Getting Started

1. **Clone or download** this repository.
2. Open the included Mini vMac app on macOS 15.5.
3. The emulator will auto-boot into the Macintosh Plus environment.
4. Use the virtual machine just like a real vintage Mac—double-click to open folders or run apps.

---

## 📁 How to Import `.sit` Files

To import and extract `.sit` (StuffIt) archive files into Mini vMac:

1. **Drag the `.sit` file** into the Mini vMac window while it's running. It will appear as `ImportFL` on the desktop.
2. Open **Import FL** from the applications folder to convert the file into the Mac file system.
3. Open **ResEdit**, and use `File > Get File/Folder Info…` to open the imported file.
4. Change the **Type** to `SIT!` and **Creator** to `SIT!` (all caps, with exclamation marks).
5. Save the changes and close ResEdit.
6. Finally, open **StuffIt Expander** and expand the `.sit` file normally.

---

## 💡 Tips

- To add more files, drag them onto the Mini vMac window while running.
- Save your changes back out by copying files to a blank disk image and ejecting it before closing.
- Customize the experience by editing the `Mini vMac.ini` (if included).

---

## 🧠 Educational Use

This setup is especially kid-friendly, featuring intuitive, creative, and educational apps. Great for:
- Teaching basic computer literacy
- Exploring history of UI/UX
- Introducing children to creativity through drawing and early learning games

---

## 📜 License

All rights to the original Macintosh software belong to their respective creators. This project is intended for educational and nostalgic use only.

---

## 🙌 Credits

- Mini vMac by Paul C. Pratt — [https://www.gryphel.com/c/minivmac/](https://www.gryphel.com/c/minivmac/)
- Software collected from Macintosh Garden & Macintosh Repository
