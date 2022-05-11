# How to launch Gnosis Chain non-validator node with Docker Compose and Nethermind

1. Install Docker Engine and Docker Compose following the original instructions https://docs.docker.com/get-docker/ and https://docs.docker.com/compose/install/

2. Clone this repo:

    ```bash
    $ git clone https://github.com/xdaichain/non-validator-ne-node-dockerized
    $ cd non-validator-ne-node-dockerized
    ```

3. Start your node.

    ```bash
    $ docker-compose up -d
    ```

After docker containers are created, the node will sync with the chain (may take a while).

To restart you need to use `docker-compose stop` and `docker-compose start` being in the `non-validator-ne-node-dockerized` directory.
