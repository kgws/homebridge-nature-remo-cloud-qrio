# homebridge-nature-remo-cloud-qrio

Homebridge Plug-in for Air Conditioner Managed by Nature Remo

Example:

```js
...

"accessories": [
  {
    "accessory": "NatureRemoCloudQrio",
    "name": "Qrio",
    "accessToken": "xxxxxxxxx_xxxxxxxxxxxxxxx_x_xxxxxx_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
    "appliance_id": ""
  }
]

...
```

* Please get your access token at https://home.nature.global/ and set it to `access_token`.
* `appliance_id` can be left blank if you only have one aircon.
