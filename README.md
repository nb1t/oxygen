# nb1t/oxygen

## Template based project generation command line utility.

<script async defer src="https://buttons.github.io/buttons.js"></script>

[![Source Code][badge-source]][source]
[![Latest Version][badge-release]][packagist]
[![Software License][badge-license]][license]
[![PHP Version][badge-php]][php]
[![Build Status][badge-build]][build]
[![Coverage Status][badge-coverage]][coverage]

[badge-source]: http://img.shields.io/badge/source-nb1t/oxygen-blue.svg?style=flat-square
[badge-release]: https://img.shields.io/packagist/v/nb1t/oxygen.svg?style=flat-square&label=release
[badge-license]: https://img.shields.io/packagist/l/nb1t/oxygen.svg?style=flat-square
[badge-php]: https://img.shields.io/packagist/php-v/nb1t/oxygen.svg?style=flat-square
[badge-build]: https://img.shields.io/travis/nb1t/oxygen/master.svg?style=flat-square
[badge-coverage]: https://img.shields.io/coveralls/github/nb1t/oxygen/master.svg?style=flat-square

[source]: https://github.com/nb1t/oxygen
[packagist]: https://packagist.org/packages/nb1t/oxygen
[license]: https://github.com/nb1t/oxygen/blob/master/LICENSE
[php]: https://php.net
[build]: https://travis-ci.org/nb1t/oxygen
[coverage]: https://coveralls.io/r/nb1t/oxygen?branch=master
[downloads]: https://packagist.org/packages/nb1t/oxygen

---
</br>

## Basic installation

Linux and windows subsystem for linux:

``` bash
curl --proto '=https' --tlsv1.2 -sSf https://oxygen.io/install.sh | sh
```

Using powershell:

``` cmd
powershell.exe -command "Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://oxygen.io/install.ps1'))"
```

Or download the prebuild binarys and installers for windows hosts.

<a class="github-button" href="https://github.com/nb1t/oxygen/archive/master.zip" data-icon="octicon-download" data-size="large" aria-label="Download the prebuild binarys from GitHub">Download (Binarys)</a>

<a class="github-button" href="https://github.com/nb1t/oxygen/archive/installer.msi" data-icon="octicon-download" data-size="large" aria-label="Download the installer from GitHub">Download (Installer)</a>

## Usage

``` bash
oxygen -h
```

Please review the docs (`docs/*`) and `USAGE.md`, for a more detailed documentation about commands and templates.

---
</br>

## Project Structure

The following shows oxygen's basic project structure.

| Name              | Description                                   |
| ------------------| --------------------------------------------- |
| **bin/**          | Commands and scripts for this project         |
| **build/**        | Cache, logs, and builded binary files         |
| **docs/**         | Project-specific documentation                |
| **storage/**      | Location of built-in templates and database   |
| **src/**          | Oxygen library and application source code    |
| **tests/**        | Automated tests for oxygen                    |

---
</br>

## Copyright and License

The nb1t/oxygen project is copyright © [Nico Duitsmann](mailto:nico.duitsmann@nord5.de)
and licensed for use under the terms of the
Apache License, Version 2.0 (Apache-2.0). Please see [LICENSE](LICENSE) and
[NOTICE](NOTICE) for more information.
