<p align="center">
  <img
    width="100%"
    alt="Qrypt"
    src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:4fd6be,50:7dd3fc,100:c4a5ff&text=Qrypt&fontColor=0b0f14&fontSize=60&fontAlign=50&fontAlignY=40&animation=fadeIn"
  />
</p>
<p align="center">
  <img alt="degoog" src="https://img.shields.io/badge/degoog_1.1.1+-0B0F14?style=for-the-badge" />
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img alt="CSS" src="https://img.shields.io/badge/CSS-663399?style=for-the-badge&logo=css&logoColor=white" />
  <img alt="License" src="https://img.shields.io/badge/GPL--3.0-red?style=for-the-badge&logo=gnu&logoColor=white" />
</p>

<p align="center">
  <img alt="Version" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2Fhidden-space-xyz%2FQrypt%2Fmaster%2Fthemes%2Fqrypt%2Ftheme.json&query=%24.version&prefix=v&style=for-the-badge&label=Version&color=2EA44F&logo=github&logoColor=white" />
  <img alt="Light and dark" src="https://img.shields.io/badge/Light_%26_Dark-0B0F14?style=for-the-badge&logo=gnometerminal&logoColor=4FD6BE" />
</p>

# 💻 Qrypt

**Qrypt is a code-focused theme for [degoog](https://github.com/degoog-org/degoog): monospace type, an
editor palette, a terminal prompt and line-numbered results, in light and dark.**

## ⭐ Features

- **🔤 Monospace Everywhere** — Uses the fonts already on the device (JetBrains Mono, Cascadia Code, Fira Code, SF Mono, Consolas…). Nothing is loaded from third parties
- **🎨 Editor Palette** — Titles look like functions, URLs like strings and engines like `@decorators`
- **⌨️ Terminal Prompt** — A prompt logo with a blinking caret, a `/` search prompt and a `// comment` footer
- **🔢 Line-Numbered Results** — An editor-style gutter numbers each result on wide screens
- **📄 At a Glance** — The summary box is framed as `glance.md`
- **✨ Motion** — The logo types itself in, the focused search bar runs a scan along its border and results cascade in. Everything stays still when the device asks for reduced motion
- **🌗 Light and Dark** — Follows degoog's appearance setting
- **🌈 Five Accents** — Mint, Amber, Violet, Cyan and Rose for the prompt, caret, focus ring and active tab
- **🏷️ Qrypt Branding** — Page and tab titles, logo, favicon and the no-JS pages all read **Qrypt**

## 📸 Screenshots

<p align="center">
  <img width="32%" alt="Qrypt home page" src="themes/qrypt/screenshots/01-home.jpg" />
  <img width="32%" alt="Qrypt results in dark mode" src="themes/qrypt/screenshots/02-results-dark.jpg" />
  <img width="32%" alt="Qrypt results in light mode" src="themes/qrypt/screenshots/03-results-light.jpg" />
</p>

## 📦 Installation

Qrypt requires degoog 1.1.1 or newer.

1. In degoog, open **Settings → Store** and add this repository:

   ```text
   https://github.com/hidden-space-xyz/Qrypt.git
   ```

2. Install **Qrypt** from the Themes list.
3. Apply it in **Settings → Themes**.

## ⚙️ Options

Open **Settings → Themes → Qrypt → Configure**:

| Option       | Values                          | Default | Effect                                                            |
| ------------ | ------------------------------- | ------- | ----------------------------------------------------------------- |
| Accent       | Mint, Amber, Violet, Cyan, Rose | Mint    | Highlight colour for the prompt, caret, focus ring and active tab |
| Line numbers | Show, Hide                      | Show    | Numbers each result in an editor-style gutter on wide screens     |
| Animations   | On, Off                         | On      | Typed logo, search bar scan and results that cascade in           |

> [!NOTE]
> degoog sets a few names in its core, outside a theme's reach, so they still read "degoog": the OpenSearch
> name used when adding the engine to a browser, the installable app manifest and the first-run tour.

## 📁 Repository

```text
Qrypt/
├── package.json           Store manifest that lists the theme for degoog
├── .github/workflows/     Weekly check of new degoog releases against the files Qrypt relies on
└── themes/qrypt/
    ├── theme.json         Theme metadata, templates and settings schema
    ├── style.css          Palette, typography, accents, results header and motion
    ├── layout.html        Page shell, favicon and Qrypt titles
    ├── index-templates/   Home logo, search box and footer
    ├── nojs/              Logo for the no-JS home page
    └── screenshots/       Images shown in the degoog Store
```

The results header is degoog's own markup restyled from `style.css`, so changes degoog makes to it reach Qrypt
without a theme update. When a new degoog release touches a file Qrypt relies on, the **degoog upstream**
workflow fails with the diff in its summary; once Qrypt is updated, set `DEGOOG_BASELINE` in the workflow to
that release.

## 💡 How to Contribute

- **Report Bugs**: Found something that looks wrong? Open an issue with a screenshot and your degoog version.
- **Suggest Features**: New accents, layouts or details are welcome as issues.
- **Send Changes**: Fork the repository, make your change and open a pull request against `master`.

## 📜 License

Qrypt is released under the [GNU General Public License v3.0](LICENSE). You are free to use, study, modify and
redistribute it, and any derivative work must carry the same license.

<p align="center">
  <img
    width="100%"
    alt=""
    src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=140&color=0:c4a5ff,50:7dd3fc,100:4fd6be&animation=twinkling"
  />
</p>
