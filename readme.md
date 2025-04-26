# F5 BIG-IP Load Balancer Demo Page

This repository contains a simple demo page intended for use with F5 BIG-IP load balancers.
It can be used to test, visualize, and troubleshoot basic load balancing configurations.

## What This Is

- Four slightly different lightweight HTML page.
- Useful for verifying load balancing behavior, session persistence, and health checks.
- No backend processing — fully static, except optional dynamic fields via JavaScript.

## Intended Use

- Demos
- Lab environments
- PoC (Proof of Concept) setups
- Educational and training purposes

## How To Use

1. Deploy the files on backend servers behind your F5 BIG-IP, nginx config file is included in the repo.
2. Access the VIP (Virtual IP) from a browser.
3. Watch which server responds as you refresh, simulate traffic, or test persistence methods.

## Requirements

- NGINX webserver
- Browser to access the page

## Disclaimer

This project is provided **AS IS** without warranty of any kind.
Use it at your own risk. No support is provided.

## License

MIT License — see LICENSE file for details.
