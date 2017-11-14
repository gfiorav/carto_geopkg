
```json
{
	"info": {
		"name": "name",
		"description": "description",
		"attributions": "attributions",
		"sources": "carto, osm",
		"classification": {
  			"tags": ["manolo", "escobar", "rey"],
			"categories": ["food", "drinks"]
	},
  	"publishing": {
	    	"privacy": "private"
  	},
	"data": {
		"source": {
			"type": "sync",
			"configuration": {
				"refresh_interval_s": 3600,
				"url": "https://foo.bar"
			}
		},
		“schema”: {
			“column_1”: {
				“type”: “Float”,
				“range”: {
					“min”: “0.0”,
					“max”: “42.0”
				}
			}
		}		
	}
}
```
