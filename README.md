# Network3
Network3 builds an AI Layer2 helping AI developers worldwide inference train or validate models widely quickly, conveniently, and efficiently

Website: [https://network3.ai](https://account.network3.ai/register_page?rc=5dd0d548)

Discord: https://discord.com/invite/q4cHgxZUCH

Telegram: https://t.me/network3official

X: https://x.com/network3_ai
# Register account

https://account.network3.ai/register_page?rc=5dd0d548

# Installation Guide for Ubuntu

### 1. Server preparation

```
sudo apt update
sudo apt install wget curl make clang net-tools pkg-config libssl-dev build-essential jq lz4 gcc unzip snapd -y
```


### 2. Download and Extract the tar file
```
cd $HOME
wget https://network3.io/ubuntu-node-v1.1.tar
tar -xf ubuntu-node-v1.1.tar
rm -rf ubuntu-node-v1.1.tar
cd ubuntu-node
```
### 3. Start node
```
sudo bash manager.sh up
```
### 4. Provides node access to your account
#### 4.1 If the Ubuntu system has a desktop environment
 You can access the dashboard directly through Firefox at: https://account.network3.ai/main
 #### 4.2  From another machine
Open a browser on the other machine and visit: https://account.network3.ai/main?o=xx.xx.xx.xx:8080
With: IP address of the Ubuntu machine is xx.xx.xx.xx and port 8080
