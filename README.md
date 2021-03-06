SS Vagrant
======================

Vagrant base VM for SilverStripe development or anything else LAMP.

## Guest OS
- CentOS 6.5 OS by [puppet labs](http://puppet-vagrant-boxes.puppetlabs.com/)
- Apache
- PHP 5.5
- MySQL
- Composer
- Git
- Pear

## Requirements
- [VirtualBox](//www.virtualbox.org)
- [Vagrant](//www.vagrantup.com)
- [Ansible](//www.ansible.com) (Unix system)

## Usage
- git submodule init
- git submodule update
- vagrant up
- www folder ready
- use localhost:8080 or 10.11.12.13 or map ss.local.dev to the IP

## Notes
This is only a development environment!
Inspired by [BetterBrief/vagrant-skeleton](https://github.com/BetterBrief/vagrant-skeleton)

## License (BSD Simplified)

Copyright (c) 2013, Thierry Francois (colymba)

All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

 * Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
 * Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
 * Neither the name of Thierry Francois, colymba nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.
 
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.