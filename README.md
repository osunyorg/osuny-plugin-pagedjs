# osuny-plugin-pagedjs

## Installation


### Installer le submodule

`git submodule add https://github.com/osunyorg/osuny-plugin-pagedjs themes/osuny-plugin-pagedjs`

### Appeler le plugin

Dans `config/_default/config.yaml` :

```
_merge: deep
theme: 
  - osuny
  - osuny-plugin-pagedjs
```

Le paramètre `merge: deep` est essentiel pour le bon fonctionnement du site !