### High v1.0.2 (macOS Apple Silicon)
- Three routing modes: **All Traffic (+ Bypass)**, **Selected Apps (Per-App)**, and **Selected Domains Only** with 1-click presets (Facebook, TikTok, Gemini, YouTube, X, Threads, ChatGPT, Claude)
- **Share Link Import** (`vless://`, `vmess://`, `trojan://`, `ss://` / Outline + multi-line paste) & V2Ray/Xray JSON support
- **Live Connections & Domain Inspector** with 1-click `+ Domains` / `+ Bypass`
- **Server Ping (`ms`)** & **Live Telemetry** (Exit IP + Country Flag, Download/Upload speed)
- Standalone DMG with bundled `xray-core` and `sing-box` (no Homebrew required)

#### First-time install note
After dragging `High.app` to `/Applications`, if macOS shows an unverified app warning, run once in Terminal:
```bash
xattr -cr "/Applications/High.app"
```
