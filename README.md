1. Copy extra.xml to $SOURCETREELOCATION/.repo/local_manifests/
2. Repo sync
2. Run `vendor/extra/patch.sh` from root of source tree
3. OMS and updater app added :D

PS: The patch.sh needs running after every `repo sync` for OMS

SOURCETREELOCATION/.repo/local_manifests/
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
  <project name="luk1337/android_vendor_extra" path="vendor/extra" remote="github" revision="cm-14.1-rootless" />
  <project name="substratum/interfacer" path="packages/apps/ThemeInterfacer" remote="github" revision="n-rootless" />
</manifest>
