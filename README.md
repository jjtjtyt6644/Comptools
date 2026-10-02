# About CompTools

**CompTools** is a modern, all-in-one system utility and diagnostics application designed to give Windows users complete control over their hardware and software environment. Built with a sleek, dark-themed UI and powered by a lightweight C# backend, CompTools streamlines everything from hardware monitoring to one-click software installations.

---

## 🌟 Key Features

### 💻 Deep System Diagnostics (Hardware Scanning)
CompTools uses native Windows Management Instrumentation (WMI) to instantly gather detailed, highly accurate information about your system without needing third-party diagnostic tools.
* **Core Components:** Identifies exact models for your CPU, GPU, Motherboard, and RAM.
* **Granular Details:** Extracts BIOS version, CPU Cores/Threads, Disk models, and System Type.
* **Network & OS:** Displays OS Build versions, Device Name, Serial Numbers, and MAC Addresses.

### 📦 Seamless Software Management (Powered by Winget)
Forget downloading installers manually. CompTools integrates directly with the Windows Package Manager (`winget`) to provide a curated grid of essential applications.
* **One-Click Installs:** Install browsers, gaming launchers, media tools, and development environments silently in the background.
* **Live Console:** Watch real-time installation progress directly within the app's integrated terminal.
* **Download History:** Keeps a log of everything you've installed through the app.

### 🚀 System Optimization & Debloating
CompTools provides quick access to powerful system tweaks designed to improve performance and remove clutter.
* **OEM Debloat:** Strip away pre-installed manufacturer bloatware and unnecessary Windows default apps.
* **Gaming & Network Modes:** Apply registry-level tweaks to prioritize system resources for gaming and optimize network adapters for lower latency.
* **Startup Manager:** Easily view and manage which applications are allowed to launch when Windows boots.

### ☁️ Cloud Sync & User Profiles
Never lose your diagnostic history or app preferences. CompTools features secure Firebase integration.
* **Multiple Sign-in Options:** Log in via Email/Password, Discord OAuth, or continue as an anonymous Guest.
* **Cloud Storage:** Automatically syncs your latest hardware scans and download history to the cloud (Firestore).
* **Cross-Device Access:** Sign in on a different machine to view the hardware profiles of your other computers and see what apps you previously installed.

### 🎨 Premium, Customizable Interface
* **Modern Aesthetic:** A sleek, glassmorphic dark mode UI built with modern web technologies (HTML/CSS/JS) hosted inside a high-performance WebView2 container.
* **Custom Backgrounds:** Personalize the app by uploading your own background images, which are saved locally and persist between sessions.

---

## 🛠️ Technical Stack
* **Frontend:** HTML, Vanilla CSS, JavaScript
* **Backend Shell:** C# / .NET 10 WPF (Windows Presentation Foundation)
* **Browser Engine:** Microsoft Edge WebView2
* **Package Management:** `winget` (Windows Package Manager)
* **Cloud / Database:** Firebase Authentication & Firestore Database
