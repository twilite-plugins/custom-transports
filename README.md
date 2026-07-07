# TwiLite custom transports

By default we use shortest-path for transport data. This repository contains ADDITIONAL transports we add on top of the data from shortest-path. Contributing to shortest-path will also add the transport to TwiLite

See: https://github.com/Skretzo/shortest-path/

## Format

Custom transports are TSV rows. Columns must be separated with **tabs**, not spaces.

```tsv
Origin	Destination	menuOption menuTarget objectID	Skills	Items	Quests	Varbits	VarPlayers	Duration	Display info
