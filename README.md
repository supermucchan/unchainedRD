# Unchained plugins

This repository stores the Unchained app official plugins repository and the plugins themselves.

A more complete description is available on the official repository of Unchained on Github

 ## Create your own

To be updated!

### repository.json

A json file with a description of the repository and the available plugins

```json
{
  "repository_version": 1.0,
  "name": "Unchained",
  "description": "Unchained main repository",
  "author": "LivingWithHippos",
  "plugins": [
  {
    "id": "etree",
    "versions": [
    {
      "plugin": 2.0,
      "engine": 2.0,
      "link": "https://gitlab.com/LivingWithHippos/unchained-plugins/-/raw/main/repository/plugins/etree/etree_v2.0.unchained"
    }
    ]
  }]
}
```

There can be multiple versions of a plugin to let people with older versions of Unchained use them.