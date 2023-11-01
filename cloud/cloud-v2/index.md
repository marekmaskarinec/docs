---
title: Cloud v2
---
import Image from '@theme/IdealImage';

# Cloud v2

[**HARDWARIO Cloud v2**](https://prod.hardwario.cloud/) offers new CHESTER device management with bidirectional communication support.

Thanks to this, even low-power battery devices can be controlled and configured remotely with:
- [**Web interface**](https://prod.hardwario.cloud/)
- [**API**](https://api.prod.hardwario.cloud/v2/documentation/index.html)

Cloud v2 improves the device's codecs. In Cloud v1 codecs had to be set manually, in v2 codecs are directly in the device's firmware and they are uploaded automatically.

## Cloud v2 structure

All your devices are placed in a **Space**. You can self-provision devices to your or other spaces.

Every device can have a **name**, **tags** and **labels**.

### Name

You can name your device so it can fill in for example its address or a specific note with it.

### Tags

Tags are useful for organizing similar devices together, or you can create a callback and connect it to the tag. So tagged devices will trigger your callback when sending uplink messages. You can have multiple tags assigned to a device.

### Labels

Labels are key-value information you can put on every device. Labels are also passed to the callback, so your callback can react to specific labels on that device.

## Connectors

Please see the [**Connectors**](connectors) article.

## API Keys

You can define multiple API keys that allow you to automate all the functions over [**API**](https://api.prod.hardwario.cloud/v2/documentation/index.html)