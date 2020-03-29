# OmniEngage

Javascript Client SDK for OmniEngage Server

## Getting Started

You need to install OmniEngage and set API credentials before you get started

If you not installed yet, you can install using below options

1. [DigitalOcean One Click Installation](https://marketplace.digitalocean.com/apps/caprover?action=deploy&refcode=27013eb71a06)  
2. [Installing by your own](https://github.com/shoppre-tech/omniengage#installing-omniengage---in-5-minutes)

## Installation

```shell script
npm i @shoppre/omniengage -S
```

## Usage

### for building emails
```json
{
 "scripts": {
    "event:fire": "./node_modules/.bin/omniengage events",
    "email-build": "./node_modules/.bin/omniengage build",
    "email-update-send": "./node_modules/.bin/omniengage update-send",
    "email-deploy": "DEBUG=q-* ./node_modules/.bin/omniengage deploy"
  }
}
```

## 
