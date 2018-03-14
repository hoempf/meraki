# Meraki Automation Scripts

This is a collection of scripts for managing Cisco Meraki networks and devices. It's main use is intended for CLI and use the ability to chain them together.

## Getting started

Follow those instructions to install the scripts on your local machine and use them for Meraki Management.

### Prerequisites

Most of the scripts use the Meraki [connector class](meraki.py) to send HTTP requests to the [Meraki API](https://dashboard.meraki.com/api_docs). The scripts depend on the awesome [Click](http://click.pocoo.org/) library for creating CLI scripts. 

### Libraries

The main external libraries used are:

* requests
* json
* [Click](http://click.pocoo.org/)

### Installing

Clone into any directory and install with:

```
pip install .
```

Or if you'd like a virtualenv:

```
$ virtualenv meraki
$ . meraki/bin/activate
(meraki) $ pip install .
```

## Authors
* **Mathias Seiler** 

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

* Meraki automation scripts: https://github.com/meraki/automation-scripts
* README.md template from [here](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2) (thanks!)
