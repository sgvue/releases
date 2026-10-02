# SGVue — downloads

SGVue is a read-only IFC model viewer for BIM coordination review. Models are parsed and viewed on your own computer and are never changed.

Download the latest version from **[Releases](https://github.com/sgvue/releases/releases)**.

## System requirements

- **System** — Windows 10 or 11, 64-bit.
- **Memory** — 8 GB works for IFC files up to about 100 MB; 16 GB is recommended for 200 MB files, or for several models together.
- **Graphics** — any graphics card with WebGL2, which every PC of the last several years has; on a PC with an NVIDIA card, SGVue uses it automatically.
- **Files** — IFC, as `.ifc` or `.ifczip`. It is built for typical files of 50–200 MB; a single file larger than 600 MB is not opened.
- **Disk** — about 110 MB to download, and about 390 MB once installed.
- **Internet** — not needed to view models. Two things use it: a check for a newer version when SGVue starts, which sends nothing about your files or models, and Ask Vee — only if you set it up with your own Anthropic API key.

## Install or update (Windows)

1. Download `SGVue-<version>-setup.exe` from the latest release.
2. Run the setup file. The app is not code-signed yet, so Windows may show "Windows protected your PC" — choose **More info → Run anyway**.
3. The setup tells you what it will do: **Install** on a new computer, **Update** when an older SGVue is installed, or **Repair** when the same version is already there. If SGVue is open, it asks to close it first.
4. On the last page, choose whether to open SGVue now and whether to keep a desktop shortcut, then click **Finish**. To pin SGVue to the taskbar, right-click it in Start and choose **Pin to taskbar**.

Updating keeps your settings, API key, recent files and saved views.

Check which version you have under **Help › About**. From version 1.2.0, SGVue's start page — where you open models — tells you when a newer version is out, and **Help › Check for updates…** opens the SGVue web page — <https://sgvue.github.io/> — which says whether you are up to date.
