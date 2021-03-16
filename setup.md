# retronhosting for wgytcraft setup
## install it
in your modules.json moduleList array add the following
```json
		"gh://retronhosting/retronhosting-wgytcraft-module"
```
## config example
in your modules.json websiteData add the following
```json
	"subdomain.domain.topleveldomain":{
      "module":"retronhosting/retronhosting-wgytcraft-module",
      "config":{
        "pagedir":"/home/runner/hosting/pages/",
        "404":"/home/runner/hosting/pages/404.html"
      }
    },
```
