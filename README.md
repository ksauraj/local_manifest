# Local Manifests for Realme G90T Series #

### Android 11 R based trees ###

```bash

# Grab Local Manifest
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/noobyysauraj/local_manifest/master/local_manifest.xml --create-dirs

# Sync
repo sync -j$(nproc --all) --force-sync
```