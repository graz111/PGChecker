[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.8+-blue)](https://www.python.org/)
[![Telegram](https://img.shields.io/badge/Telegram-SeaChecker-2CA5E0?logo=telegram&logoColor=white)](https://t.me/seachecker)
[![GitHub stars](https://img.shields.io/github/stars/graz111/PGChecker?style=social)](https://github.com/graz111/PGChecker)

> **Important:** This tool does not take responsibility for any accounts or data extracted and used from sites. Use at your own risk.

Made by **UntitledScripter** · Full Recode 2026

<p align="center">
  <img src="https://github.com/graz111/PGChecker/blob/main/image1.png?raw=true" alt="PGChecker v2.0 interface" width="838" />
  <br><em>PGChecker v2.0 interface</em>
</p>

## Features

- 8 powerful search modes (full lines or clean `email:pass`)
- Extremely fast processing of large TXT files
- Duplicate removal in combined modes
- RU / ENG interface
- "Only login:pass" filter option
- Auto-save or manual save results

### Search Modes

| Mode                         | What it saves                              | Description |
|------------------------------|--------------------------------------------|-------------|
| pekora.zip / auth / accountlogin | Full lines with file info                 | Classic pekora format |
| ecsr.io / auth / login       | Full lines with file info                 | Ecsr format |
| Ecsr.io & Pekora.zip         | Full lines, deduplicated                  | Both templates at once |
| kornet.lat                   | Data matching kornet.lat pattern          | Kornet logs |
| pwndab.xyz                   | Data matching pwndab.xyz pattern          | Pwndab format |
| bbblox.fit                   | Data matching bbblox / bbb fit            | Blox variations |
| All In                       | Clean `email:pass` only                   | All templates (except pekora) |
| Custom                       | Based on your custom regex                | Fully customizable |

## Quick Start

Run the script:

```bash
python PGChecker.py or just run PGChecker.exe
