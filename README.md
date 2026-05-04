# Cloudflared Install

This repository contains a script to install the [Homebrew package manager](https://brew.sh/) and the [`cloudflared` package](https://github.com/cloudflare/cloudflared#cloudflare-tunnel-client) in `appdev-projects` codespaces.

More specifically, the script:
1. Installs brew.
2. Adds Homebrew to your bash configuration file to ensure all future terminals you open can find the `brew` command.
3. Installs the `cloudflared` package with Homebrew.

This script makes assumption about the machine it's being run on so we only guarentee that it runs successfully on GitHub Codespaces.
