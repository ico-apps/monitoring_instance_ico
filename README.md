# monitoring_instance_ico
Config files for ICO monitoring app

## SOCC - Seguiment d'Ocells Comuns de Catalunya
## SEGRE - Seguiment General de Rapinyaires Forestals
## Plataformes 

## .env installed protocols
```
INSTALLED_PROTOCOLS=ico_monitoring.protocols.base,ico_monitoring.protocols.socc,ico_monitoring.protocols.plataformes,ico_monitoring.protocols.segre
```

## Active submodules

```
[submodule "ico_monitoring/protocols/socc"]
	path = ico_monitoring/protocols/socc
	url = git@github.com:ico-apps/monitoring_socc.git

[submodule "ico_monitoring/protocols/segre"]
	path = ico_monitoring/protocols/segre
	url = git@github.com:ico-apps/monitoring_segre.git

[submodule "ico_monitoring/protocols/plataformes"]
	path = ico_monitoring/protocols/plataformes
	url = git@github.com:ico-apps/monitoring_plataformes.git
```
