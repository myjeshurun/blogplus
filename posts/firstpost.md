---
title: "Part 1: Using OnlyDomains to register a new domain测试"
description: This is a post describing how to set up a domain using onlydomains.com.
date: 2020-12-13
tags:
  - onlydomains
layout: layouts/post.njk
image: https://gist.githubusercontent.com/0-vortex/8c1147b957f88b7ceaa85d3b22843803/raw/b04507cbedd3e21055df25c28b281e94bb119117/splash-onlydomains.jpg
---

## What is OnlyDomains

[![OnlyDomains splash logo](https://gist.githubusercontent.com/0-vortex/8c1147b957f88b7ceaa85d3b22843803/raw/b04507cbedd3e21055df25c28b281e94bb119117/splash-onlydomains.jpg)](https://www.onlydomains.com)
测试

[OnlyDomains](https://onlydomains.com) is a great domain registrar with lightning-fast domain name activation and customer support, the only two important metrics for this tutorial. The full list of potential bottlenecks is endless, here are some of my favorites:

- **account registration complexity**: domain identity forces you to have a loose KYC verification with your service provider and as such it can depend on a lot of things.
- **account security options**: multi-factor authentication, IP address whitelisting, session management, etc with a variable level of paranoia.
- **domain identity management**: before actually purchasing a domain name, you should have a clear sense of the legal and public contact information, sometimes this step is auto-completed and requires adjustment.
- **payment processor verification**: while most of the global gateways enable for an almost instant check-out, verification processes can require additional information.
- **name server manipulation**: this one should be straightforward but it ultimately depends on the TLD you picked for your domain name.
- **DS record manipulation**: the DS record, being generated by a third party, requires manual intervention from most service providers.

## Using OnlyDomains

### Sign up for a new account

In order to successfully manage a domain you need to set up an account with a domain name registrar.

Proceed to logging in or create a new account:

![sign up](https://gist.githubusercontent.com/0-vortex/8c1147b957f88b7ceaa85d3b22843803/raw/e9b2f4bba1d9023c87881108bed95f8b1490683a/onlydomains-sign-up.png)

### Enable multi-factor authentication

Once registered, make sure to set up at least one type of multi-factor authentication.

![two factor](https://gist.githubusercontent.com/0-vortex/8c1147b957f88b7ceaa85d3b22843803/raw/e9b2f4bba1d9023c87881108bed95f8b1490683a/onlydomains-two-factor.png)

### Register a new domain name

Spend some time deciding what name identity you want to go with, or just pick a fast and easy to set up gTLD like `.online` and be done with it:

![domain register](https://gist.githubusercontent.com/0-vortex/8c1147b957f88b7ceaa85d3b22843803/raw/e9b2f4bba1d9023c87881108bed95f8b1490683a/onlydomains-domain-register.png)

### Update domain name servers

Click on "Domains" -> "My Domains", and a page listing all your domains should load. Right next to your newly registered domain there should be a pencil icon, right under the "Edit" table header.

Clicking that icon should load the domain summary page:

![domain summary](https://gist.githubusercontent.com/0-vortex/8c1147b957f88b7ceaa85d3b22843803/raw/58503764c213405e646bcb0815577b5f383eadad/onlydomains-domain-summary.png)

Click the "Edit" button that is next to "Name Server" listing and update your name servers as instructed by CloudFlare:

![domain dns settings](https://gist.githubusercontent.com/0-vortex/8c1147b957f88b7ceaa85d3b22843803/raw/58503764c213405e646bcb0815577b5f383eadad/onlydomains-domain-dns-settings.png)
