[![Tests][tests-badge]][tests-link]
[![GitHub Release][release-badge]][release-link]
[![Go Report Card][report-badge]][report-link]
[![License][license-badge]][license-link]<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-5-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->


# hostctl

> Manage your /etc/hosts like a pro!

This tool gives you more control over the use of your `hosts` file. You can have multiple profiles and enable/disable as you need.


## Why?

It is a tedious task to handle the `hosts` file by editing manually. With this tool you can automate some aspects to do it cleaner and quick. 


## Features

  * Manage groups of host names by profile.
  * Enable/disable complete profiles.
  * Add/remove groups of host names.
  * Add profiles directly from a `.etchosts` file that you can add to your git repo or any VCS.
  * Sync a profile with Docker or Docker Compose containers.
  

## Documentation

Read the [Getting started guide](http://guumaster.github.io/hostctl/getting-started) 
or check full documentation [here](http://guumaster.github.io/hostctl).


## Sample Usage
![sample usage](docs/hostctl.gif)


## Installation

Go to [release page](https://github.com/guumaster/hostctl/releases) and download the binary you need.

Or read how to install on your system [here](http://guumaster.github.io/hostctl/installation/)


## Linux/Mac/Windows and permissions

The tool recognize your system and use the right hosts file, it will use `/etc/hosts` on Linux/Mac and `C:/Windows/System32/Drivers/etc/hosts` on Windows.

**SUDO/ADMIN**: You will need permissions for any action that modify hosts file, add `sudo` to the commands below when needed. If you are on windows, make sure you run it as administrator.

**WARNING**: it should work on any system. It's tested on Ubuntu and Windows 10. If you can confirm it works on other system, please let me know [here](https://github.com/guumaster/hostctl/issues/new).

## Contributing

Be sure to read [CONTRIBUTING](CONTRIBUTING.md) and [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md).


## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/gkze"><img src="https://avatars0.githubusercontent.com/u/3131232?v=4" width="50px;" alt=""/><br /><sub><b>George Kontridze</b></sub></a><br /><a href="https://github.com/guumaster/hostctl/commits?author=gkze" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/pacodes"><img src="https://avatars2.githubusercontent.com/u/28688410?v=4" width="50px;" alt=""/><br /><sub><b>Pacodes</b></sub></a><br /><a href="https://github.com/guumaster/hostctl/commits?author=pacodes" title="Tests">⚠️</a> <a href="https://github.com/guumaster/hostctl/commits?author=pacodes" title="Code">💻</a></td>
    <td align="center"><a href="https://772424.com"><img src="https://avatars3.githubusercontent.com/u/64371?v=4" width="50px;" alt=""/><br /><sub><b>BarbUk</b></sub></a><br /><a href="https://github.com/guumaster/hostctl/commits?author=BarbUk" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/devopsbrett"><img src="https://avatars1.githubusercontent.com/u/4403441?v=4" width="50px;" alt=""/><br /><sub><b>Brett Mack</b></sub></a><br /><a href="https://github.com/guumaster/hostctl/commits?author=devopsbrett" title="Code">💻</a></td>
    <td align="center"><a href="https://peterthaleikis.com"><img src="https://avatars0.githubusercontent.com/u/8433587?v=4" width="50px;" alt=""/><br /><sub><b>Peter Thaleikis</b></sub></a><br /><a href="https://github.com/guumaster/hostctl/commits?author=spekulatius" title="Code">💻</a> <a href="https://github.com/guumaster/hostctl/commits?author=spekulatius" title="Documentation">📖</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!


## Author(s)

* [guumaster](https://github.com/guumaster)


## LICENSE

 [MIT license](LICENSE)




<!-- JUST BADGES & LINKS -->
[tests-badge]: https://img.shields.io/github/workflow/status/guumaster/hostctl/Test
[tests-link]: https://github.com/guumaster/hostctl/actions?query=workflow%3ATest

[release-badge]: https://img.shields.io/github/release/guumaster/hostctl.svg?logo=github&labelColor=262b30
[release-link]: https://github.com/guumaster/hostctl/releases

[report-badge]: https://goreportcard.com/badge/github.com/guumaster/hostctl
[report-link]: https://goreportcard.com/report/github.com/guumaster/hostctl

[license-badge]: https://img.shields.io/github/license/guumaster/hostctl
[license-link]: https://github.com/guumaster/hostctl/LICENSE

