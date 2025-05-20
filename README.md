# PS4 DNS Block List

Welcome to the **PS4 DNS Block List**. This repository contains a curated list of domains to block on your DNS (e.g., NextDNS, Pi-hole, custom DNS server) to restrict unwanted activity on your PlayStation 4 console.

## Purpose

This blocklist is designed for users who want to:

- Prevent **firmware updates** from being downloaded or installed.
- Block **game and app updates**.
- Disable or limit **PSN login/authentication**.
- Stop **telemetry and tracking** from Sony servers.

This is especially useful for users who want to preserve a jailbreak-compatible firmware version or avoid forced system updates.

## What's Included

The list targets several categories of PlayStation domains:

- **Firmware update servers** (`*.ps4.update.playstation.net`, `update.playstation.net`)
- **Content delivery networks** used by Sony and third parties
- **PSN authentication and login services**
- **Game update servers**
- **Telemetry and logging endpoints**

## How to Use

### With NextDNS

1. Go to [https://my.nextdns.io](https://my.nextdns.io).
2. Select your configuration.
3. Navigate to the **Denylist** section.
4. Copy and paste the domains from the blocklist file—**one per line**.
5. Save your configuration.

> Note: NextDNS currently does not support importing external lists via URL.

### With Pi-hole or Custom DNS

1. Download the blocklist file.
2. Add the domains to your blacklist.
3. Restart DNS services to apply changes.

## Disclaimer

Blocking these domains may disable access to certain features, such as:

- PSN Store
- Friends & messaging
- Trophy syncing
- Cloud saves

Use at your own risk. This list is intended for advanced users familiar with the risks and limitations of blocking network activity on a console.

## Contributing

If you find additional domains worth blocking, feel free to open an issue or submit a pull request with your suggestions.

## License

This project is licensed under the MIT License. You are free to use, share, and modify this list.

---