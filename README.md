# PM2 Cron Example

This repository contains a basic cron job example that is written in NodeJS and deployed using docker

## How to start this locally?

### Requirements

- [NodeJS](https://nodejs.org/en/)
- [pm2](https://pm2.io/) (`npm install -g pm2`) [Process manager for NodeJS]

### Steps to start

Run following command on your terminal

```sh
pm2 start processes.json --no-daemon
```

## How to run with Docker?

```sh
docker build --platform linux/amd64 -t YOUR_IMAGE_NAME .
```
