# suckless-st (Simple Terminal) - Customized by Rohan Batra

A personal fork of the [suckless](https://suckless.org/) `st` (simple terminal) project, featuring version separation and custom configurations tailored to my workflow.

---

## 🧩 About

This repository is a modified version of the minimalist `st` terminal emulator. It builds on the original `st` philosophy of simplicity, speed, and suckless design by incorporating personal patches and tweaks.

**Key Goals:**
- Maintain the minimalist essence of `st`
- Add selected patches for usability
- Keep versions clearly separated for clarity and modular updates

---

## 🚀 Features

- Versioning for better patch and configuration management (`v0.9`)
- Clean separation of patches and custom configs
- Maintains upstream compatibility
- Lightweight and fast

---

## 🛠️ Installation

### Prerequisites

Make sure you have the following installed:

- `make`
- `gcc`
- `libX11`
- `libXft`
- `fontconfig`

### Clone and Build

```bash
git clone https://github.com/rohanbatrain/suckless-st.git
cd suckless-st
sudo make clean install
```

To install for your user only (no `sudo`):

```bash
make clean install PREFIX=$HOME/.local
```

---

## 🧪 Usage

Just run:

```bash
st
```

To set `st` as your default terminal emulator in your `.xinitrc`, `.xsession`, or window manager config, update it like:

```bash
exec st
```

---

## 🧬 Customization

This fork is intentionally versioned (e.g., `v0.9`) to experiment with configurations and keep things modular. You can:

- Tweak font, color scheme, and key bindings in `config.h`
- Apply additional [suckless patches](https://st.suckless.org/patches/)
- Track upstream changes easily

---

## 🧾 Version History

| Version | Description            | Date       |
|---------|------------------------|------------|
| v0.9    | Version Separation     | May 3, 2023|

---

## 📜 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT), same as the original suckless `st`.

---

## 🤝 Credits

- [suckless.org](https://suckless.org) for the original `st`
 
 
