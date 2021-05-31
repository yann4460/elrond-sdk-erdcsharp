# elrond-sdk-erdcsharp
[![Build status](https://github.com/ElrondNetwork/elrond-sdk-erdcsharp/actions/workflows/dotnet.yml/badge.svg)](https://github.com/ElrondNetwork/elrond-sdk-erdcsharp/actions/workflows/dotnet.yml)  [![Package](https://img.shields.io/nuget/v/elrond-sdk-erdcsharp)](https://www.nuget.org/packages/elrond-sdk-erdcsharp/)

Elrond C# SDK for interacting with the Elrond Network (in general) and Smart Contracts (in particular).

This SDK depends on : 
* [BouncyCastle](https://www.nuget.org/packages/Portable.BouncyCastle/) for ed25519 and other crypto algorithms
* [dotnetstandard-bip39](https://github.com/elucidsoft/dotnetstandard-bip39) for mnemonic / seed phrase.

## How to install ? 

Elronford SDK for .NET Core is delivered via nuget package, therefore it can be installed as follows:

`Install-Package elrond-sdk-erdcsharp`

# Main Features
* Transaction construction, signing, broadcasting and querying.
* Smart Contracts deployment and interaction (execution and querying).
* Wallet creation, derive wallet from mnemonic
* Query values stored within Smart Contracts.

# Documentation
The [documentation](./docs/index.md) can be found following this link.

# Change Log
All notable changes will be documented in this file.