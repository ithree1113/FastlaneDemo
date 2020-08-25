fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew install fastlane`

# Available Actions
## iOS
### ios register_app
```
fastlane ios register_app
```

### ios get_development_cert
```
fastlane ios get_development_cert
```

### ios get_development_provisioning_profile
```
fastlane ios get_development_provisioning_profile
```

### ios get_adhoc_provisioning_profile
```
fastlane ios get_adhoc_provisioning_profile
```

### ios get_dev_certs
```
fastlane ios get_dev_certs
```

### ios sync_device_info
```
fastlane ios sync_device_info
```
Update iOS UDUD's on Developer Portal
### ios sync_all_development
```
fastlane ios sync_all_development
```
Sync team Development assets
### ios sync_signing_assets
```
fastlane ios sync_signing_assets
```
Sync team Code-Signing assets
### ios bootstrap_code_signing
```
fastlane ios bootstrap_code_signing
```

### ios build_appstore
```
fastlane ios build_appstore
```
Build for App Store submission
### ios build_adhoc
```
fastlane ios build_adhoc
```
Build for Ad Hoc submission
### ios pilot_lane
```
fastlane ios pilot_lane
```

### ios distribute_to_appstore
```
fastlane ios distribute_to_appstore
```

### ios release
```
fastlane ios release
```


----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
