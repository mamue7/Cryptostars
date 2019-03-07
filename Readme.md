# Cryptostars Project

This Project creates a ERC-721 star token to register, buy and exchange stars. The corresponding app can be used to register stars and lookup star information. 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Project Details

Used Tools:

Truffle v5.0.5
openzeppelin-solidity 2.1.2
MetaMask
Infura

Token Details:

ERC-721 Token Name: Cryptostars

ERC-721 Token Symbol: CST

Token Address on the Rinkeby Network: 0x60635AF3143bfFe4baCb1497eCF8d2862745Bdcb

### Prerequisites

Installing Node and NPM is pretty straightforward using the installer package available from the (Node.jsÂ® web site)[https://nodejs.org/en/].

## Deploy contract

Local Dev Environment:

truffle develop 
> compile
> migrate --reset

Rinkeby Environment: (edit truffle-config.js with your MetaMask Seed & Infura Key)

truffle migrate --reset --network rinkeby

## Run App

Go into sub folder 'app'.

Run command 'npm run dev' to start web server.

## Authors

Martin Müller
