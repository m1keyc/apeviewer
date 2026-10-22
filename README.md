<p align="center"><img src="https://apeviewer.com/app.png" width="96" alt="APE Viewer"></p>

# APE Viewer

Remote desktop for **Windows, Mac and Linux**. Each remote monitor gets its own window or full screen on the display you choose.

**[Choose your download](https://apeviewer.com/downloads)** · [Website](https://apeviewer.com) · [Help](https://apeviewer.com/help) · [Releases](https://github.com/m1keyc/apeviewer/releases)

## Platforms

| Platform | Current download | Scope |
| --- | --- | --- |
| Windows 10/11, x64 | [Stable installer](https://github.com/m1keyc/apeviewer/releases/latest/download/APEViewerSetup.exe) | Connect and share; full Windows app |
| macOS 13+, Apple Silicon | [Viewer preview](https://apeviewer.com/downloads#preview-notes) | Connect to a Windows PC; real Mac acceptance ongoing |
| Linux x64, glibc 2.36+ | [Viewer preview](https://apeviewer.com/downloads#linux-setup) | Connect to a Windows PC; X11 or Wayland desktop |

Mac/Linux are early viewer previews. They do not yet share a native desktop, transfer files, draw or show app-only streams. Linux clipboard is X11 only. Native device/Keychain testing is ongoing; previews update by downloading the next build. See [current requirements and feature matrix](https://apeviewer.com/downloads).

## What it does

- Keep each remote screen separate: move, resize or make it full screen without squeezing every monitor into one picture.
- Connect on your home network, from anywhere over the internet with Premium, or through the optional Tailscale module.
- Use mouse and keyboard, with sound, clipboard and controllers where supported by the platform.
- Choose each person's access, require approval and disconnect people. Windows hosting supports screen or app restrictions, file transfer, drawing and per-person controller permissions.
- Pair with a code shown on the shared PC, or sign in with your account. End-to-end desktop encryption authenticates the computers, including over the internet.
- Windows sharing supports NVIDIA, AMD and Intel video encoding. Native preview viewers use their bundled video libraries; performance depends on your hardware and network.

## Free and Premium

| | Free | Premium |
| --- | --- | --- |
| Shared PCs | 1 | Unlimited |
| Devices you connect from | Unlimited | Unlimited |
| Screens at once | 1, switch any time | All of them |
| People connected at once | 1 | Up to 4 |
| Controllers | 1 | Up to 4 where supported |
| Home network / optional Tailscale | Yes | Yes |
| Connect from anywhere over the internet | No | Yes |

Launch prices: **$6.99/month or $49/year** (regular $9.99/$79.99). Yearly saves 42% compared with twelve launch-price monthly payments. New subscribers have a 1-day free trial; launch subscribers keep their price while subscribed. Checkout, billing terms and availability: [Account](https://apeviewer.com/account#plan).

Prefer to pay once? **Lifetime Premium is $199.99** for all Premium features on one personal account for the lifetime of the APE Viewer service. No trial or renewal. Lifetime purchases are non-refundable except where required by law or Whop's buyer-protection rules. Platform preview limits still apply, and internet features require the service to remain available. Try Free on your setup first. [Choose Lifetime](https://apeviewer.com/account?period=lifetime#plan) · [Lifetime Terms](https://apeviewer.com/terms#lifetime-premium).

## Getting started

1. Install the Windows app on the PC you want to reach and turn on sharing in Hosting.
2. Download the viewer for the computer you connect from. Use the same Windows app on Windows, or the appropriate Mac/Linux preview.
3. Sign in, choose your PC and its screens, and connect. For pairing without account discovery, enter the code shown on the shared PC.

Never connect to a computer without its owner's permission. Keep the OS keychain/keyring and security protections enabled. [Setup and troubleshooting](https://apeviewer.com/help).

## Libraries and source

The current application source is proprietary and private. Releases through 0.5.6 retain their original MIT license.

Native previews dynamically link FFmpeg under LGPL 2.1 or later and OpenH264 under its BSD source license. Each native download includes notices and has a matching codec source/build archive on the same release page. Those components retain their modification, replacement and applicable reverse-engineering rights. [Notices and sources](https://apeviewer.com/downloads#third-party).

Problems: [Help and report form](https://apeviewer.com/help#report). Support: support@apeviewer.com.
