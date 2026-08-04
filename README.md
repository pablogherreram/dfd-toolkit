<div align="center">
  <img src="assets/logo-full.png" alt="DFD Toolkit Logo" width="600">

  <br><br>

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  [![Visual Studio Code](https://img.shields.io/badge/VS%20Code-Extension-blue.svg)](https://code.visualstudio.com/)
  [![JavaScript](https://img.shields.io/badge/Made%20with-JavaScript-F7DF1E.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

  <p align="center">
    <b>A powerful VS Code extension to parse, inspect, and modernize classic DFD files.</b>
  </p>
</div>

---

## 🚀 Overview

**DFD Toolkit** bridges the gap between classic algorithmic education and modern software development. Designed for students, educators, and developers, this lightweight extension reads legacy `.dfd` (Diagramas de Flujo) files and instantly translates their internal token logic into modern, readable formats directly inside Visual Studio Code.

## ✨ Key Features

- 🔍 **Deep File Parsing & Diagnostics:** Decodes the internal token structure of legacy `.dfd` files safely.
- 📝 **Pseudocode Generation:** Automatically translates diagram blocks into clean, readable pseudocode.
- 📊 **Mermaid Charts:** Renders the flow structure into standard Mermaid graphs for easy visualization and markdown embedding.
- ⚙️ **JSON Data Structuring:** Extracts inputs, processes, decisions, and outputs into a structured JSON format for easy debugging.
- 🚀 **Seamless Integration:** Works natively as a custom read-only editor inside VS Code. 

## 🛠️ Built With

- **[JavaScript / Node.js](https://nodejs.org/)** - Core parsing and logic engine.
- **[VS Code Extension API](https://code.visualstudio.com/api)** - UI integration and custom editor provider.

## 🚧 Roadmap & Development

DFD Toolkit is in active development. We are continuously mapping standard DFD tokens to expand our parsing capabilities:

- [x] Basic I/O Tokens (Outputs `4`, Inputs `5`)
- [x] Process & Assignment Tokens (`6`)
- [x] Decision Tokens (`7`, `8`)
- [ ] Loop Tokens (While / *Mientras* `9`) - *In Progress*
- [ ] For Loop Tokens (*Para*)

## 📦 Installation (Coming Soon)

We are preparing the extension for the **VS Code Marketplace**. 
Currently, the extension can be tested locally by cloning this repository, installing the dependencies, and launching the Extension Development Host.

## 📄 License

This project is distributed under the [MIT License](LICENSE). See the `LICENSE` file for more information.
