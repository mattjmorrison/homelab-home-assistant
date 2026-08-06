# homelab-home-assistant

Home Assistant deployment for the homelab k3s cluster, managed via ArgoCD.

Home Assistant is a home automation platform that integrates with a wide range of smart home devices. Accessible at `home-assistant.morrisons.site`. Runs with `hostNetwork: true` to support local device discovery (mDNS/Zeroconf) for integrations like Philips Hue, Chromecast, and other LAN-based devices.

Configuration is persisted in a PersistentVolumeClaim at `/config`.

---

[Homelab Docs](https://github.com/mattjmorrison/homelab/blob/main/docs/INDEX.md)
