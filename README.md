# Agent OS — download

Agent OS runs AI agents on your own computer, with your own accounts.

## Install

1. Download the file for your computer from the latest release:
   - **Windows:** `agentos-node-<version>.zip`
   - **macOS / Linux:** `agentos-node-<version>.tar.gz`
2. Unzip it and run the installer from inside the folder:
   - Windows: `powershell -ExecutionPolicy Bypass -File .\install.ps1`
   - macOS / Linux: `./install.sh`
3. Open the address it prints. You sign in once with your own Agent OS account — there is no password.
   The first person to sign in owns that computer.
4. In the app, connect your own Claude account. Your agents think with your account, never anybody else's.

You need an Agent OS account to sign in. The installer fetches Node.js and Claude Code itself if your
computer does not have them.

## Check what you downloaded

Each release lists the SHA-256 of its files. On Windows: `Get-FileHash <file>`; elsewhere: `sha256sum <file>`.
