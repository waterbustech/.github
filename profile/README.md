## Waterbus

> [!WARNING]
> We’re migrating to **V3** — a fully rebuilt backend in **Rust**, powered by [**str0m**](https://github.com/algesten/str0m) — a **sans-IO WebRTC implementation** for maximum performance, flexibility, and control over media handling.  
> This release brings advanced **live streaming**, **adaptive media delivery**, and **bandwidth-efficient calls**, engineered for **low deployment costs** and **exceptional quality**.

## 🪐 Overview

**Waterbus** is a modern **open-source video conferencing platform** built with **Flutter**, **Rust**, and **WebRTC** (via **str0m**).  
It powers **virtual meetings, webinars, live streaming, and real-time collaboration** — delivering smooth audio/video, screen sharing, interactive chat, and more.

Whether you run it for your **team**, **organization**, or integrate it into **your own product**, Waterbus is designed for:

- 🟢 **Cross-platform** — Web, Desktop, and Mobile.
- ⚡ **Ultra-low latency** — Rust-powered SFU built on **str0m**’s sans-IO design.
- 🌍 **Scalable architecture** — From 1-on-1 calls to large events.
- 💡 **Developer-friendly** — APIs, SDKs, and modular design.

## 🛰️ Live Services

| Service | Purpose |
|---------|---------|
| [**meet.waterbus.tech**](https://meet.waterbus.tech) | 🌟 **Showcase demo** — Video conferencing, webinars, and live streaming |
| [**waterbus.tech**](https://waterbus.tech) | 📢 Product landing page & feature overview |
| [**docs.waterbus.tech**](https://docs.waterbus.tech) | 📖 Developer documentation & API reference |
| [**changelog.waterbus.tech**](https://changelog.waterbus.tech) | 📝 Release notes & version history |
| [**status.waterbus.tech**](https://status.waterbus.tech) | 📡 Real-time service status |

## 📦 Key Features

- **High-quality Audio/Video** — Powered by [WebRTC](https://webrtc.org/) via **[str0m](https://github.com/algesten/str0m)**
- **Adaptive Stream & Dynacast** —  
  • Dynamically pause unused video layers to cut bandwidth and save device power  
  • Automatically adjust video quality based on view size and visibility  
- **Hybrid Topology** — Start peer-to-peer for 1-on-1 calls, seamlessly switch to SFU for group calls  
- **Live Streaming (HLS / LL-HLS)** — Broadcast to thousands with minimal delay  
- **Adaptive Bandwidth** — Dynamic quality switching for smooth playback in any network condition  
- **Secure & Private** — End-to-end encryption for calls

## 💬 Community

Waterbus uses **Zulip** for open-source collaboration — join the conversation, ask questions, and contribute ideas.

<a href="https://zulip.com/"><img width="70" src="https://raw.githubusercontent.com/zulip/zulip/main/static/images/logo/zulip-icon-circle.svg" alt="Zulip logo"></a>  
[Join Waterbus Chat](https://waterbus.zulipchat.com/)

## 🤝 Contributing

We welcome contributions from developers, testers, and documentation writers of all experience levels.

Waterbus is licensed under the **Apache 2.0 License**.
