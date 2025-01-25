# ![veld chain](https://raw.githubusercontent.com/veldhub/.github/refs/heads/main/images/symbol_V_letter.png) veld_chain__demo_conllueditor

This repo contains a [chain veld](https://zenodo.org/records/13322913) encapsulating 
https://github.com/Orange-OpenSource/conllueditor on sample data.

## requirements

- git
- docker compose (note: older docker compose versions require running `docker-compose` instead of 
  `docker compose`)

Clone this repo with all its submodules
```
git clone --recurse-submodules https://github.com/veldhub/veld_chain__demo_conllueditor.git
```

## how to reproduce

**[./veld.yaml](./veld.yaml)** 

Starts a conllueditor instance, which can be reached at http://localhost:8888/ . Open the veld yaml 
file for more information.

```
docker compose -f veld.yaml up
```

