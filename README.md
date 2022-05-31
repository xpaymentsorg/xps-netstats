# xps-netstats
xPayments Network Status.

## Prerequisite
* node
* npm

## Installation
Make sure you have node.js and npm installed.

Clone the repository and install the dependencies

```bash
git clone https://github.com/xpaymentsorg/xps-netstats
cd xps-netstats
npm install
sudo npm install -g grunt-cli
```

##Build the resources
NetStats features two versions: the full version and the lite version. In order to build the static files you have to run grunt tasks which will generate dist directories containing the js and css files, fonts and images.


To build the full version run
```bash
grunt
```

##Run

```bash
npm start
```

see the interface at http://localhost:3000

It is a fork of eth-netstats.<br>
Official eth-netstats Repository: https://github.com/cubedro/eth-netstats<br>
