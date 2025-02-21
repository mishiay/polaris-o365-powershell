# Rubrik Polaris Microsoft 365 Protection PowerShell Module

Welcome to the Rubrik Microsoft 365 Protection
[PowerShell](https://docs.microsoft.com/en-us/powershell/) module! This module
provides an SDK for writing PowerShell scripts that work with the Rubrik
Polaris Microsoft 365 protection product, allowing you to view all O365 users,
their current SLA assignment and change those SLA assignments.

## :hammer: Installation

```powershell
Import-Module ./RubrikPolaris/RubrikPolaris.psd1 
```

Additional information can be found in the [Quick Start Guide](QUICK_START.md).


### Requirements

* PowerShell v6.0 or greater
* [Microsoft Graph PowerShell SDK](https://docs.microsoft.com/en-us/powershell/microsoftgraph/installation?view=graph-powershell-1.0) (`Install-Module Microsoft.Graph`) v1.8.0 or later
* When creating SharePoint Enterprise Applications with the `New-EnterpriseApplication` cmdlet, the script must be run as an administrator and the following dependencies must be installed:
    * OpenSSL. When running on Windows, only [openssl-3.4.1](https://slproweb.com/products/Win32OpenSSL.html) is supported.

## :mag: Example

See [Quick Start Guide](QUICK_START.md) for examples.

## :blue_book: Documentation

Here are some resources to get you started! If you find any challenges from this project are not properly documented or are unclear, please raise an issue and let us know! This is a fun, safe environment - don't worry if you're a GitHub newbie! :heart:

* [Quick Start Guide](QUICK_START.md)
* [Rubrik API Documentation](https://github.com/rubrikinc/api-documentation)

## :muscle: How You Can Help

We glady welcome contributions from the community. From updating the documentation to adding more functions for Python, all ideas are welcome. Thank you in advance for all of your issues, pull requests, and comments! :star:

* [Contributing Guide](CONTRIBUTING.md)
* [Code of Conduct](CODE_OF_CONDUCT.md)

## :pushpin: License

* [MIT License](LICENSE)

## :point_right: About Rubrik Build

We encourage all contributors to become members. We aim to grow an active, healthy community of contributors, reviewers, and code owners. Learn more in our [Welcome to the Rubrik Build Community](https://github.com/rubrikinc/welcome-to-rubrik-build) page.

We'd  love to hear from you! Email us: build@rubrik.com :love_letter:
