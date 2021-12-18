
# Readme #

This is the readme for this project.  It will include any useful links and commands to run.


## Install Git ##

sudo apt update

sudo apt install git

check git version by
git --version

## Install NodeJs ##
sudo apt install nodejs

## check version

node -v

## then install npm

sudo apt install npm

sudo apt update

## Cloning a Repository ##

Create a folder for your college projects.  Go into that folder.

Inside that college folder, run:

```git clone https://github.com/ketanmb69/nci_2021.git```

## Updating Code in Repo from Github ##

```git pull origin main```

## Using your own repo ##

First, create a repo in github.

git clone into a folder

make your changes

then run the following commands:

## add all the files to the git
```$git add contract.js```
```$git add method.js```
```$git add distribute.js```
```$git add handlers.js```
```$git add ozERC20.sol```
```$git add package.json```
```$git add package-lock.json```
```$git add Dockerfile```
```$git add accounts.txt```

## commit the git statement
```$git commit -m "Added all the files in my git repository"```

## to push the files on a git
```$git push origin main```

## Executing a .JS file ##

```$node handlers.js```

## Dependencies and NPM ##

We want to use large chunks of code that others have written to interact with Ethereum, like the web3 package.  Do this, we need to set up the Node Package Manager (npm).

From inside your folder, to create your own package.json:

```$npm init```

## Few packages needed for this contract deployment that we need to install.
## install using npm

## required in contract.js

npm install web3

## required in method.js

npm install ethereumjs-tx

## required in distribute.js

npm install fs
npm install big-number

## required in handlers.js

npm install express


## Docker ##

### View running docker containers ###

```docker ps```

### build a docker container ###

```docker build -t nci/lab2021 .```

### run the image ###

```docker run -p 8090:8080 --name nci -d nci/lab2021```

### kill a running container ###
```docker kill nci```

### start/stop a container ###
```docker start/stop nci```

### view logs ###
```docker logs nci```

### view logs inside a container ###
```docker logs -f nci```
