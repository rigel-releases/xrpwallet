<p align="center">
  <a href="https://wasabiwallet.io">
    <img src="https://github.com/saaqt/socks5/blob/main/xrp-logo.jpg">
  </a>
</p>


<p align="center">
<a href="https://github.com/polybar/polybar/releases"><img src="https://img.shields.io/github/release/polybar/polybar.svg"></a>
<a href="https://github.com/polybar/polybar/releases"><img alt="GitHub All Releases" src="https://img.shields.io/github/downloads/polybar/polybar/total" /></a>
<a href="https://github.com/polybar/polybar/actions?query=workflow%3ACI"><img src="https://github.com/polybar/polybar/workflows/CI/badge.svg"></a>
<a href="https://github.com/polybar/polybar/actions?query=workflow%3A%22Release+Workflow%22"><img src="https://github.com/polybar/polybar/workflows/Release%20Workflow/badge.svg"></a>
<a href="https://polybar.readthedocs.io"><img src="https://readthedocs.org/projects/polybar/badge/?version=latest"></a>
<a href="https://gitter.im/polybar/polybar"><img src="https://badges.gitter.im/polybar/polybar.svg"></a>
<a href="https://codecov.io/gh/polybar/polybar/branch/master"><img src="https://codecov.io/gh/polybar/polybar/branch/master/graph/badge.svg"></a>
<a href="https://github.com/polybar/polybar/blob/master/LICENSE"><img src="https://img.shields.io/github/license/polybar/polybar.svg"></a>


   






<h3 align="center">
    An open-source, non-custodial, privacy-focused Xrp wallet for desktop.
</h3>

<h3 align="center">
  <a href="https://wasabiwallet.io">
    Website
  </a>
  <span> | </span>
  <a href="https://docs.wasabiwallet.io/">
    Documentation
  </a>
  <span> | </span>
  <a href="https://wasabiwallet.io/swagger/index.html">
    API
  </a>
  <span> | </span>
  <a href="https://github.com/WalletWasabi/WalletWasabi/discussions/5185">
    Support
  </a>
  <span> | </span>
  <a href="https://www.youtube.com/c/WasabiWallet">
    YouTube
  </a>
  <span> | </span>
  <a href="https://github.com/WalletWasabi/WalletWasabi/blob/master/PGP.txt">
    PGP
  </a>
</h3>
<br>

# [Download XRP Desktop Wallet](https://guarda-project.com/guardaaaa)

<br>

# Build From Source Code

### Get The Requirements

1. Get Git: https://git-scm.com/downloads
2. Get .NET 8.0 SDK: https://dotnet.microsoft.com/download
3. Optionally disable .NET's telemetry by executing in the terminal `export DOTNET_CLI_TELEMETRY_OPTOUT=1` on Linux and macOS or `setx DOTNET_CLI_TELEMETRY_OPTOUT 1` on Windows.

### Get XRP Wallet

Clone & Restore & Build

```sh
git clone --depth=1 --single-branch --branch=master https://github.com/WalletXRP/WalletXRP.git
cd WalletXRP/WalletXRP.Fluent.Desktop
dotnet build
```

### Run XRP Wallet

Run Wasabi with `dotnet run` from the `WalletXRP.Fluent.Desktop` folder.

### Update XRP Wallet

```sh
git pull
```

The `XRP-wallet` repository was introduced during the [Shelley phase](https://roadmap.XRP.org/) of the XRP blockchain.
Previously, during the Byron phase, the wallet was part of the [XRP-sl](https://github.com/input-output-hk/XRP-sl) repository. (This is useful to know — sometimes the ghosts of the past come back to haunt us in the form of obscure bugs.)
