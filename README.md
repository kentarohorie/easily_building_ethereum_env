# Build

Create developing environment with docker

```
docker-compose up

docker-compose exec ether sh

geth --datadir /home/ether_test/eth_private_net init /home/ether_test/eth_private_net/myGenesis.json

geth --networkid "15" --nodiscover --datadir "/home/ether_test/eth_private_net" console 2>> /home/ether_test/eth_priv
ate_net/geth_err_log --port 30000

```

# References

- https://book.ethereum-jp.net/first_use/connect_to_private_net.htmlhttps://book.ethereum-jp.net/first_use/connect_to_private_net.html
