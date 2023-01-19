[![FINOS - Incubating](https://cdn.jsdelivr.net/gh/finos/contrib-toolbox@master/images/badge-incubating.svg)](https://community.finos.org/docs/governance/Software-Projects/stages/incubating)

# Symphony Windows HWND Helper

When sharing a screen on Citrix with media optimization enabled with the SymphonyElectron app, the Symphony Windows HWND Helper will provide the right hnwd (HWND corresponding to main content  BrowserView) .
## Installation

Windows with npm installed:

```sh
npm run build
``````

## Usage example

```
SymphonyNativeWindowHandleHelper HWND
```
Returns the right BrowserView HWND

## Development setup

Ensure Visual Studio is installed.



## Contributing
For any questions, bugs or feature requests please open an [issue](https://github.com/finos/SymphonyWindowsHwndHelper/issues)
For anything else please send an email to help@finos.org.

To submit a contribution:
1. Fork it (<https://github.com/finos/SymphonyWindowsHwndHelper/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Read our [contribution guidelines](.github/CONTRIBUTING.md) and [Community Code of Conduct](https://www.finos.org/code-of-conduct)
4. Commit your changes (`git commit -am 'Add some fooBar'`)
5. Push to the branch (`git push origin feature/fooBar`)
6. Create a new Pull Request

_NOTE:_ Commits and pull requests to FINOS repositories will only be accepted from those contributors with an active, executed Individual Contributor License Agreement (ICLA) with FINOS OR who are covered under an existing and active Corporate Contribution License Agreement (CCLA) executed with FINOS. Commits from individuals not covered under an ICLA or CCLA will be flagged and blocked by the FINOS Clabot tool (or [EasyCLA](https://community.finos.org/docs/governance/Software-Projects/easycla)). Please note that some CCLAs require individuals/employees to be explicitly named on the CCLA.

*Need an ICLA? Unsure if you are covered under an existing CCLA? Email [help@finos.org](mailto:help@finos.org)*

## License

Copyright 2023 Symphony LLC

Distributed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

SPDX-License-Identifier: [Apache-2.0](https://spdx.org/licenses/Apache-2.0)
