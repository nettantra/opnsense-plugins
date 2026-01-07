# NetTantra OPNsense Plugin Repository

## Installation

Run the following commands on your OPNsense device:

```bash
# Download repository configuration
fetch -o /usr/local/etc/pkg/repos/nettantra.conf https://raw.githubusercontent.com/nettantra/opnsense-plugins/main/nettantra.conf

# Update package cache
pkg update -f
```

## Available Plugins

After adding the repository, go to **System > Firmware > Plugins** and enable
"Show community plugins" to see available packages.

## Manual Installation

If you prefer to install manually:

```bash
pkg install os-nettantra-uptimestatus
```
