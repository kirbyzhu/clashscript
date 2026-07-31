# Quantumult X rules

## Apple direct routing

Add this under Quantumult X `[filter_remote]`, then update the resource:

```ini
https://raw.githubusercontent.com/kirbyzhu/clashscript/refs/heads/main/QXconf/AppleDirect.list, tag=Apple Direct, force-policy=direct, update-interval=172800, opt-parser=false, enabled=true
```

Keep this resource enabled. It sends Apple ID, App Store, iCloud, APNs and Apple CDN traffic directly through the local network rather than a proxy.
