<p align="center">
  <img height="100" height="auto" src="https://github.com/freshe4qa/vistara/assets/85982863/22a65f88-c69a-4731-9812-2d48dff3e0ed">
</p>

# Vistara

Official documentation:
>- [Guide](https://docs.vistara.dev/)

Explorer:
>- [-](-)

### Minimum Hardware Requirements
 - 2x CPUs; the faster clock speed the better
 - 2GB RAM
 - 40GB of storage (SSD or NVME)

```
sudo apt update && sudo apt upgrade -y
```

```
apt install curl iptables build-essential git wget jq make gcc nano tmux htop nvme-cli pkg-config libssl-dev libleveldb-dev tar clang bsdmainutils ncdu unzip libleveldb-dev -y
```
```
curl -L https://vistara-labs.github.io/vimana/install.sh | bash && vimana init
```
```
vimana run celestia light-node --network arabica --rpc consensus-validator.celestia-arabica-10.com
```
