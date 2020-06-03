## Mettre à jour l'Overlay depuis le déploiement du nouveau node

### Cliquer sur le logo tampermonkey, puis sur Tableau de bord

![ici](https://github.com/macadelic80/jklm-overlay/blob/master/tuto1.png)

### Puis cliquer sur JKLM Overlay

![ici](https://github.com/macadelic80/jklm-overlay/blob/master/tuto2.png)

### et remplacer

```
// ==UserScript==
// @name         JKLM Overlay
// @namespace    http://tampermonkey.net/
// @version      0.1
// @description  Bombparty Overlay + JKLM autolinker
// @author       Macadelic
// @match        https://jklm.fun/*
// @match        https://phoenix.jklm.fun/games/bombparty/
// @grant        none
// ==/UserScript==
```
### par
```
// ==UserScript==
// @name         JKLM Overlay
// @namespace    http://tampermonkey.net/
// @version      0.1
// @description  Bombparty Overlay + JKLM autolinker
// @author       Macadelic
// @match        https://jklm.fun/*
// @match        https://*.jklm.fun/games/bombparty/
// @grant        none
// ==/UserScript==
```


### Vous devrez normalement obtenir:

![ici](https://github.com/macadelic80/jklm-overlay/blob/master/tuto3.png)

### Puis faire CTRL+S pour sauvegarder
