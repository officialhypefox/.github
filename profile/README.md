<div align="center">

<img src="https://cdn.hypefox.net/brands/hypefox/logo/icon.svg" width="88" alt="Hypefox">

# Hypefox AB

**Internet infrastructure, built and run from Malmö, Sweden.**

We operate our own network and put our own brands on top of it. One of them is free, one of them is premium, and the wires underneath are the same.

[![hypefox.net](https://img.shields.io/badge/hypefox.net-101322?style=for-the-badge)](https://www.hypefox.net) [![AS214365](https://img.shields.io/badge/AS214365-HypefoxNet-5808fb?style=for-the-badge)](https://as214365.peeringdb.com) [![Malmö, Sweden](https://img.shields.io/badge/Malmö-Sweden-006AA7?style=for-the-badge)](https://www.hypefox.net)

</div>

<br>

## 🦊 The brands

<table>
<tr>
<td width="50%" valign="top">

<img src="https://www.velrix.net/img/graphics/logo.svg" height="44" alt="Velrix">

### Velrix

**Free hosting that stays free.**

Discord bots and applications, deployed in minutes. A full control panel, DDoS protection, and points you earn to keep things running. No credit card and no trial clock.

[Landing](https://www.velrix.net) · [Status](https://status.velrix.net) · [Discord](https://discord.gg/DWPW4XsWkK)

</td>
<td width="50%" valign="top">

<img src="https://cdn.hypefox.net/brands/melonslab/logo/icon.svg" height="44" alt="Melonslab">

### Melonslab

**Premium Swedish cloud.**

VPS, web hosting and game servers, all of it in Sweden. Full EU data sovereignty, GDPR by default, 100% renewable energy, and FoxProtect™ on every service.

[Landing](https://melonslab.com) · [Status](https://status.melonslab.com) · [Discord](https://discord.gg/nRRxebJDdT)

</td>
</tr>
</table>

## 🛰️ The network

Everything runs on **[AS214365](https://as214365.peeringdb.com)**, our own network out of Malmö. Routing, peering and DDoS filtering are ours to fix rather than a vendor's to explain, which is the entire reason we run it ourselves.

## 📦 Open source

Most of what we build is private. The parts that belong to the community are not:

| Repository | What it is |
| :-- | :-- |
| **[velrix-control](https://github.com/officialhypefox/velrix-control)** | Our fork of [Pelican Panel](https://github.com/pelican-dev/panel), AGPL-3.0. Single sign-on, rate limits tuned for a brokered API, and a few interface fixes. Every change is listed in its readme, as the licence asks. |
| **[velrix-eggs](https://github.com/officialhypefox/velrix-eggs)** | The eggs behind Velrix deployments, with an automated icon pipeline. |

We keep our forks merged with upstream rather than letting them drift.

## 🔒 Behind the closed doors

The rest is private, but there is no reason to be cagey about what it is. This is what we actually work on:

| | Repository | What it is | Built with |
| :-- | :-- | :-- | :-- |
| ❇️ | `velrix-web` | the Velrix site and dashboard | Nuxt 4, Nuxt UI |
| ❇️ | `velrix-api` | the Velrix API, economy and panel broker | Bun, Hono, Drizzle, PostgreSQL, Redis |
| ❇️ | `velrix-discord` | the Velrix bot, for people who live in Discord | Bun, discord.js, Sapphire |
| ❇️ | `velrix-desktop` | desktop app with its own update channel | Electron, Vite |
| 🍉 | `melonslab-web` | the Melonslab landing page | Nuxt 4, Tailwind |
| 🦊 | `hypefox-web` | this company, on the web | Nuxt 4, Nuxt UI |

## 📮 Getting hold of us

- **Support** · open a ticket from the dashboard of the service you use, or ask in its Discord: [Velrix](https://discord.gg/DWPW4XsWkK), [Melonslab](https://discord.gg/nRRxebJDdT)
- **Security** · `contact@hypefox.net`, or see [security.txt](https://www.velrix.net/.well-known/security.txt)
- **Abuse** · `abuse@hypefox.net`
- **Peering** · [PeeringDB](https://as214365.peeringdb.com)

<div align="center">
<br>
<sub>Hypefox AB · Malmö, Sweden · AS214365</sub>
</div>
