Container and test project for tinyDTLS
=======================================

Pulls in both tinyDTLS and Contiki as git submodules to make
maintenance easy (possible).

Getting started
===============

Make sure the submodules are updated:

    git submodule update --init

setup tinyDTLS

    ./setup.sh

Make the tinyDTLS example:

    cd ./tinydtls
    make TARGET=redbee-econotag

That should make a `dtls-client_redbee-econotag.bin`

**That's all for now :)**
