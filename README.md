vm
==
A data journalism virtual machine image for VirtualBox

## Features
- csvkit
- Python
- Git
- Django
- SQLite
- MySQL
- PostgreSQL
- PostGIS
- PANDAS
- Ilene
- virtualenv/virtualenvwrapper
- QuantumGIS
- Node.js
- NPM
- Ruby
- Rails
- RVM
- Bower
- Grunt
- Fabric
- Yeoman

## Requirements
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads) (Choose your operating system)
- `git`
- `curl`
- About 10 GB of disk space locally or on an external HDD/thumbdrive
- some time

## Installing the Virtual Machine
With VirtualBox installed, kick open terminal and type:
```bash
$ git clone git@github.com:cirlabs/vm.git
$ cd vm
$ bash install-vm.sh
```
`install-vm.sh` does the following:

1. Installs the virtualbox extension pack
2. Downloads the 3 GB virtual machine image from Amazon S3
3. Imports it into VirtualBox and configures it
4. Starts the virtual machine

## Help
[Open an issue](https://github.com/cirlabs/vm/issues)

## Thanks
Thanks to [xdissent](https://github.com/xdissent) for his work on [ievms](https://github.com/xdissent/ievms). I borrowed a lot of the VirtualBox fetch and check code from there.

## License
MIT. See [LICENSE](https://github.com/cirlabs/vm/blob/master/LICENSE) for more information
