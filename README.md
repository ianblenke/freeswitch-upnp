# ianblenke/freeswitch-upnp

This is a docker-compose harness that shows how upnp can be used to run freeswitch without `--net=host`

There are submodules in this project. Be sure to initialize them first:

    git submodule update --init

To test this, run:

    docker-compose up

If you don't have `docker-compose` yet, try `pip install docker-compose` first.
