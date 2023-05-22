[![Discuss at #website:ansible.com on Matrix](https://img.shields.io/matrix/website:ansible.com.svg?server_fqdn=ansible-accounts.ems.host&label=Discuss%20at%20%23website:ansible.com&logo=matrix)](https://matrix.to/#/#website:ansible.com)

This repository contains the assets required to build the Ansible Community website. Welcome!

See the WIP site at https://ansible-community.github.io/community-website/

## Contributing to the website

Please see [CONTRIBUTING](CONTRIBUTING.md)

## Governance

Please see [Governance](CONTRIBUTING.md#Governance)

## Contacting the maintainers

The Website Working group can be found in [Ansible Website WG](https://matrix.to/#/#website:ansible.com) on Matrix
or ``#ansible-website`` on IRC. Alternatively, a GitHub issue is also acceptable for asking
questions.

## Using this repository

This repo contains the source used to generate a static site using [Nikola](https://getnikola.com/).

Configuration file for the site is ``conf.py``.

### Requirements

    pip install --upgrade -r ./requirements.txt

Visit [Nikola installation documentation](https://getnikola.com/getting-started.html#install) for more details about the site generator.

### Building and viewing the site

To build the site::

    nikola build

To see it::

    nikola serve -b

To check all available commands::

    nikola help

## Code of Conduct

Please see [CODE OF CONDUCT](CODE_OF_CONDUCT.md)

## License

[![License: CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-sa/4.0/)

## Thank you

Ansible depends on community involvement - thank you for being a part of it!
