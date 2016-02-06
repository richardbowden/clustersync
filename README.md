# clustersync
An ansible built syncthing cluster..

The idea is to build a multi server cluster using Syncthing and Ansible.

**this is a work in progress**

Each server will have the following installed to form a cluster (removes the need to use public discover and relay servers)

* syncthing client
* discovery server
* relay server

*Tasks*

Syncthing
* [x] Download and install
* [ ] Set to auto start

Discover
* [ ] Download and install
* [ ] Set to auto start
* [ ] Get service id, store as fact

Relay
* [ ] Download and install
* [ ] Set to auto start
* [ ] Get service id, store as fact

Syncthing
* [ ] Configure with discover and realy settings


#Usage

user only config is set in a file `./ansible/private_config.yml`

**THIS IS NOT CHECKED INTO GIT**

syncthing_user: username - the user to run syncthing as, the user you want files to sync for
