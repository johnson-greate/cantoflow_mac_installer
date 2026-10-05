# CantoFlow for Mac

CantoFlow is a menu-bar voice transcription app for Apple Silicon Macs.

This repository contains release information and download instructions only.
The application source code is not published here.

## Requirements

- Apple Silicon Mac (M1 or later)
- macOS 13 or later
- Internet connection for the first Qwen3 ASR model installation
- About 3 GB temporary free disk space for that first model preparation

## Install

1. Download `CantoFlow.dmg` from the [latest release](https://github.com/johnson-greate/cantoflow_mac_installer/releases/latest).
2. Open the DMG and drag `CantoFlow.app` into `Applications`.
3. Open CantoFlow from Applications.
4. If macOS blocks the first launch, open **System Settings → Privacy & Security** and choose **Open Anyway**.

## First-time setup

1. Allow **Microphone**, **Accessibility**, and **Input Monitoring** permissions when macOS asks.
2. Open **Settings → Models** and install **Qwen3 ASR** if it is not already ready.
3. Your administrator will send your personal license by WhatsApp. Open **License Info…**, paste the `CF1...` license string, and choose **Activate / Renew**.

4. For Cantonese filler cleanup or English output, configure an LLM API key or a local LLM in Settings. Choose **英文輸出** from the menu to translate your dictation directly into English.

## License

The same app supports personal, customer and student use. Your administrator sets
the license period, including 99-year long-term licenses. Existing valid trial
licenses continue to work. Licenses are sent individually via WhatsApp; do not
post your license string in a group chat or public channel.

An expired license stops recording and new file processing. Open **License Info…**
to activate or renew. English output needs an available LLM; if translation fails,
the app shows an error instead of pasting the raw Chinese transcript.

## Verify the download

Download `CantoFlow.dmg.sha256` beside the DMG and, in that download folder, run:

```bash
shasum -a 256 -c CantoFlow.dmg.sha256
```

This should report `CantoFlow.dmg: OK`.

## Support

Contact your administrator with a screenshot of the error and your macOS version.
