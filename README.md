# Cosmos
All materials related to Cosmos 

# Installation 

## Install Cosmos 
wget https://raw.githubusercontent.com/stake-capital/cosmos/master/gaia_install.sh

## Run script
1. `sudo mv gaia_install.sh /usr/local/bin/ `

2. `sudo chmod +x /usr/local/bin/gaia_install.sh`

3. `sudo /usr/local/bin/gaia_install.sh`

## Start cosmos instance 
Run `sudo systemctl start gaiad.service`

## Logs 
Run `journalctl -u gaiad -f`

# Update Cosmos 
wget https://github.com/stake-capital/cosmos/blob/master/gaia_update.sh

Update the version of the sdk into the file. 

Run: 

`chmod +x gaia_update.sh`

`./gaia_update.sh`


# Different chains

## Game of stakes
https://github.com/stake-capital/game-of-stakes

## Gaia-900x


# Register for Genesis 

## Genesis Collector

Genesis Collector by Certus One: https://genesis.certus.one/

## Chain viewer

https://hubble.figment.network/chains/genki-1000

# Networks 

Genki-2000: https://github.com/certusone/genki-2000

Genki-3000: https://github.com/certusone/genki-3000

IRISnet Testnet : Fuxi-5000 (https://medium.com/@kidinamoto/how-to-join-irisnet-testnet-fuxi-5000-77328d8219d4)

