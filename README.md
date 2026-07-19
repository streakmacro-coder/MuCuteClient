<p align="center">
  <img src="images/logo.png" alt="Modified Client Logo" width="200"/>
</p>

# Modified Client: A Utility Client for Minecraft Bedrock

**Modified Client** is an open-source utility client made for **Minecraft Bedrock Edition**. It uses a **MITM (Man-in-the-Middle)** approach to provide powerful gameplay enhancements — **without modifying the game client directly**.

---

## 📦 Version Support

- **Latest Minecraft Version**: 1.26.33
- **Supported Versions**: 1.26.33 and compatible Bedrock releases
- **Protocol Support**: Updated for Minecraft Bedrock 1.26.33

### Version 1.26.33 Features
- Fixed texture bleeding on custom blocks when using automatic block face UV assignment with undersized textures
- Full compatibility with all Bedrock Edition 1.26.33 protocol changes

---

## 🔧 Features

- **Non-Intrusive Enhancement**: Works without altering the Minecraft client, keeping your installation clean and untouched.  
- **Advanced Packet Control**: Enables in-depth control and manipulation of packet-level data.  
- **Smooth Performance**: Designed for stable connections and low-lag interaction.  
- **User-Friendly Interface**: Clean and intuitive UI built for mobile usability.  
- **Cross-Platform Support**: Compatible with all **Minecraft Bedrock Edition** platforms via Android MITM control.
- **Version 1.26.33 Ready**: Fully compatible with the latest Minecraft Bedrock updates.

---

## 📱 Platform Support

- Supports all **Minecraft Bedrock Edition platforms** through MITM:
  - **Android**
  - **iOS**
  - **Windows 10 & 11**
  - **Nintendo Switch**
  - **Xbox (limited support)**

---

## 🛠️ How to Build

To build Modified Client using **Android Studio**, follow these steps:

1. **First compile MuCuteRelay**:  
   Follow the build instructions here:  
   [https://github.com/OpenMITM/MuCuteRelay](https://github.com/OpenMITM/MuCuteRelay)

2. After compiling MuCuteRelay, locate the generated file:
   ```
   MuCuteRelay/build/libs/MuCuteRelay.jar
   ```

3. **Copy `MuCuteRelay.jar` into this project**:  
   Place the `.jar` file inside:
   ```
   app/libs/
   ```

4. **Open Modified Client in Android Studio**.

5. **Assemble the APK**:  
   Go to **Build → Assemble 'app'**.  
   After building, the APK will be located at:
   ```
   app/build/outputs/apk/debug/
   ```

---

## License

Modified Client is licensed under the **GNU General Public License v3.0 (GPLv3)**.

### ✅ Permitted Uses

- Personal use and modification.  
- Creating content (e.g., videos or showcases) using Modified Client.  
- Redistributing the original or modified source code, provided you include the same GPLv3 license and make the source code available.

### ❌ Prohibited Uses

- Distributing modified versions **without** including source code and the GPLv3 license.  
- Using the Modified Client name or logo in a way that implies official affiliation or endorsement.  
- Claiming ownership of the project or its original source code.

For full license information, visit:  
[https://www.gnu.org/licenses/gpl-3.0.en.html](https://www.gnu.org/licenses/gpl-3.0.en.html)

---

## 🤝 Contributions

We welcome and appreciate contributions from the community!  
Whether it's code, bug reports, suggestions, or documentation — every bit helps improve **Modified Client**.

---

## ❤️ Special Thanks

- **CaiMuCheng** – Package, UI & Relay  
- **LodingGlue** – Modules  
- **MrPokeG** – Modules & UI  
- **lyssadev** – Partial TXPacker Logic  
- **Answer2** – Functions  
- **Hax0r** – Partial ProtoHax Source Code

---

## ⚠️ Disclaimer

Modified Client is not affiliated with Mojang Studios, Microsoft, or any official Minecraft development team.

Use Modified Client at your **Own Risk**.  
We are **not responsible** for any bans, penalties, or issues that may result from using this client.

**Always follow server rules and respect community standards.**
