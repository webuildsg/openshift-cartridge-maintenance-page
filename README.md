# OpenShift Maintenance Page

> During the deployments when `hot_deploy` isn't enabled you see the default `503` page of the Apache Server.
This cartridge will replace this page with another one which is much more user friendly :)

![](https://cloud.githubusercontent.com/assets/553140/17082820/78c82f0c-51bd-11e6-985d-2ff4362589f4.png)

## Add Maintenance Page Cartridge

```sh
  rhc cartridge add https://raw.githubusercontent.com/webuildsg/openshift-cartridge-maintenance-page/master/metadata/manifest.yml -a <appname>
```

## Customization

To customize the 503 page, you can edit the `503.html` [here](lib/503.html).
