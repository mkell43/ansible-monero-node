Monero Node
===========

A role to deploy a monero mining node.

Requirements
------------

This role has only been tested on Ubuntu 16.04 (Xenial), use anywhere else at your own risk.  Or, even better, submit a pull request with fixes that got it working on your platform.

Example Playbook
----------------

    - hosts: monero-nodes
      roles:
         - mkell43.monero-node

License
-------

MIT

Additional Information
----------------------

Find out more about monero at https://getmonero.org/ and https://moneroworld.com/.

At this time, late November 2017, you will need a disk with around 30G free to run a full monero node.  I have one running on a VPS at [DigitalOcean](https://digitalocean.com) and another on [Vultr](https://vultr.com).

If you would like to help me in keeping those running please feel free to donate a lil' or sign up with one of those hosting providers using a referral link below.

* DigitalOcean - https://m.do.co/c/e827f39edacd
* Vultr - https://www.vultr.com/?ref=7227729
* XMR - `4Adq5EZWCJ2jh4kttRSoa3KegN3K3KVnkZdATgd1XQcnZt7cJmggXHkjXqrT3anyZ22j7DEE74GkbVcQFyH2nNiC3c7HGvC`
* BTC - `3NDB2vgQEvje1qEYeGVLBWU5oqaGcFKq5D`
