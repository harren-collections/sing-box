---
icon: material/note-remove
---

!!! failure "Removed in sing-box 1.12.0"

    GeoIP is deprecated in sing-box 1.8.0 and removed in sing-box 1.12.0, check [Migration](/migration/#migrate-geoip-to-rule-sets).

### Structure

```json
{
  "route": {
    "geoip": {
      "path": "",
      "download_url": "",
      "download_detour": ""
    }
  }
}
```

### Fields

#### path

The path to the sing-geoip database.

`geoip.db` will be used if empty.

#### download_url

The download URL of the sing-geoip database.

Default is `https://github.com/SagerNet/sing-geoip/releases/latest/download/geoip.db`.

#### download_detour

The tag of the outbound to download the database.

Default outbound will be used if empty.