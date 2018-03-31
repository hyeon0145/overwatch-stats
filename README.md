# Overwatch Stats
A Python library to query a player's overwatch stats from Battle.net

## Requirements
- Python 3.5+
- requests
- lxml
- inflect
- asyncio
- aiohttp
- async_timeout

## Installation
	pip install overwatch-stats

## Usage
	import overwatch.stats
	stats = overwatch.stats.query('pc', 'kr', '현종환#3104')

# API
## overwatch.stats.query(platform, region, battle_tag)
Queries a player's stats from the Battle.net. 
### Parameters
- `platform`: `pc`, `xbl` or `psn`
- `region`: `kr`, `us` or `eu`
- `battle_tag`: the player's battle tag
