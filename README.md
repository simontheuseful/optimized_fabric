# 🧵 Optimized Fabric

**Optimized Fabric** provides pre-configured, performance-tuned Minecraft Fabric servers for multiple versions.  
Each server build includes an optimized setup, essential performance mods, and simple startup scripts for both Windows and Linux.

---

## 🚀 Features

- **Optimized `server.properties`** for better performance and stability  
- **Fabric** pre-installed
- **Cross-platform startup scripts**
  - `start-windows.bat` → Start server on Windows
  - `start-linux.sh` → Start server on Linux  
- Includes the **best server-side optimization mods**

⚠️ **Important:**  
Do **not** start the server directly using `server.jar`.  
Always use the included startup scripts to ensure proper initialization.

---

## 🧩 Included Mods

| Mod | Description |
|---|---|
| [**Alternate Current**](https://modrinth.com/mod/alternate-current) | Reimplements redstone dust logic for huge performance gains and reduced lag. |
| [**Concurrent Chunk Management Engine (C2ME)**](https://modrinth.com/mod/c2me-fabric) | Multi-threaded chunk generation and loading to utilize all CPU cores efficiently. |
| [**Chunky**](https://modrinth.com/mod/chunky) | Pre-generates chunks to prevent lag spikes during gameplay. |
| [**FerriteCore**](https://modrinth.com/mod/ferrite-core) | Reduces memory usage through data structure optimization. |
| [**Krypton**](https://modrinth.com/mod/krypton) | Optimizes the server networking stack for lower latency and bandwidth usage. |
| [**Lithium**](https://modrinth.com/mod/lithium) | Improves server performance through logic and physics optimizations without altering vanilla behavior. |
| [**PacketFixer**](https://modrinth.com/mod/packetfixer) | Fixes packet desync and NBT transmission issues to improve connection stability. |
| [**ServerCore**](https://modrinth.com/mod/servercore) | Adds deep optimizations to entity ticking, chunk management, and server logic. |
| [**Very Many Players (VMP)**](https://modrinth.com/mod/vmp-fabric) | Optimizes for servers with large player counts by improving packet handling and entity iteration. |

📝 *Note: Some versions may include slightly different mod combinations depending on compatibility.*

---

## ⚙️ Installation

1. **Download** the pre-configured server folder for your desired Minecraft version.  
2. **Run** the appropriate start script:
   - Windows → `start-windows.bat`
   - Linux → `start-linux.sh`
3. Allow the server to generate initial files and accept the EULA in `eula.txt`.
4. Start the server again to complete setup.

---

## 📝 RAM

Maximum RAM is set to 8GB. If you want to change this please edit the start script and change both the `-Xms8192M -Xmx8192M` to your desired amount.
