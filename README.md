# DevFest Vienna
## The Distributed Web

### IPFS Example

To access IPFS via a web browser it is necessary to go through a gateway. You can run a gateway on your local
(http://localhost:8080/...) machine or use a public gateway such as the one provided by IPFS
(https://gateway.ipfs.io/...)

Content can retrieved by IPFS hash which changes with each revision.

> https://gateway.ipfs.io/ipfs/QmTZtJZYSjAe7cC68p4BfoxQdzK6rX7Hme5YFnQAhKcnZe/

By IPNS hash which remains constant.

> https://gateway.ipfs.io/ipns/QmeZuVZ6cywSymPu3BfoVWkbYhZr5GAuZfzKo4PjKaqrCM/

Or via a regular domain which has a `DNS TXT` record containing `dnslink=/ipns/QmeZuVZ6cywSymPu3BfoVWkbYhZr5GAuZfzKo4PjKaqrCM`

> https://gateway.ipfs.io/ipns/wi.llia.ms/

### Links

* BitTorrent - http://www.bittorrent.com/
* IPFS - https://ipfs.io/
  * clients - https://github.com/ipfs/ipfs#api-client-libraries
* Ethereum Project (including Swarm and Whisper) - https://www.ethereum.org/
* MediaChain - http://www.mediachain.io/
* Blockstack - https://blockstack.org
* Namecoin - https://namecoin.org/
* Syncthing - https://syncthing.net/
* Twister - http://twister.net.co/
* Spokes - http://githubengineering.com/building-resilience-in-spokes/
* GitTorrent - http://gittorrent.org/
