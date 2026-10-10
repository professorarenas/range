# Professor Arenas Ranges

A Ludus source: blueprints for cybersecurity lab ranges.

## Add it to Ludus

    ludus source add https://github.com/professorarenas/range

## Blueprints

| ID | What it deploys | RAM |
| --- | --- | --- |
| starter-lab | One Debian 12 server | 2 GB |

## Layout

    source.yml                  source metadata
    blueprints/<id>/
        blueprint.yml           display metadata
        range-config.yml        the range config

To add a lab, create a new folder under `blueprints/` with those two files, then commit and push.
