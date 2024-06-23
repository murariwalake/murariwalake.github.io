# murariwalake.github.io

This is a static website hosted on GitHub Pages.

## Accessing the Website

You can visit the website at: [murariwalake.com](http://murariwalake.com)

## DNS Configuration

The DNS records for the domain have been updated to point to GitHub Pages. The configuration was done through the Hostinger control panel.

### Steps to Update DNS Records

1. Log in to your Hostinger account.
2. Navigate to [Hostinger's DNS Zone Editor](https://hpanel.hostinger.com/domain/murariwalake.com/dns).
3. Update the DNS records as follows:

    - **A Records**:
        | Type | Name | Value             | TTL  |
        |------|------|-------------------|------|
        | A    | @    | 185.199.108.153   | Auto |
        | A    | @    | 185.199.109.153   | Auto |
        | A    | @    | 185.199.110.153   | Auto |
        | A    | @    | 185.199.111.153   | Auto |

    - **AAAA Records** (optional, for IPv6 support):
        | Type | Name | Value                 | TTL  |
        |------|------|-----------------------|------|
        | AAAA | @    | 2606:50c0:8000::153   | Auto |
        | AAAA | @    | 2606:50c0:8001::153   | Auto |
        | AAAA | @    | 2606:50c0:8002::153   | Auto |
        | AAAA | @    | 2606:50c0:8003::153   | Auto |

    - **CNAME Record**:
        | Type  | Name | Value               | TTL  |
        |-------|------|---------------------|------|
        | CNAME | www  | murariwalake.github.io | Auto |

## Repository Information

This repository contains the source code for the static website hosted on GitHub Pages.
