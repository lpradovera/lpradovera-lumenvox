Ansible LumenVox role
=========

Installs (LumenVox)[http://www.lumenvox.com/] speech recognition and text-to-speech servers and client.

Requirements
------------

Ansible 2.1 is required due to usageof `yum_repository`

Role Variables
--------------

The main playbook variable you will need is `license_servers` to point your new LumenVox installation to your license server.

Example Playbook
----------------

```
  - hosts: all
    become: yes

    roles:
      - { role: lpradovera.lumenvox, license_servers: "192.168.11.22" }
```
License
-------

MIT License:

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Author Information
------------------

Original author: (Luca Pradovera)[https://github.com/lpradovera]
